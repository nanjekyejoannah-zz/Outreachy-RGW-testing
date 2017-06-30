git clone https://github.com/aws/aws-sdk-cpp
cd aws-sdk-cpp
mkdir build
cd
cmake -DCMAKE_BUILD_TYPE=Debug ../
make aws-cpp-sdk-s3 (building and installing the entire SDK is time and space consuming)

cd ~/
git clone https://github.com/cpp-netlib/uri.git
cd uri
git submodule update --init --recursive
mkdir unl
cd unl
cmake ../uri -DCMAKE_BUILD_TYPE=Debug \
-DUri_USE_STATIC_CRT=0 -DUri_WARNINGS_AS_ERRORS=0
make
make install DESTDIR=/home/ali/uri_install

cd ~/
mkdir client
cd client
(move the Makefile and s3client.cc over)
(change the paths in the Makefile)
make

(build vstart target for ceph and run it with -n -l -r if kraken branch or --rgw_num 1 if master)
(build vstart target for ceph and run it with -n -l --rgw_num 1)
# the following are the keys provided by vstart.sh
export AWS_ACCESS_KEY_ID=0555b35654ad1656d804 \
AWS_SECRET_ACCESS_KEY=h7GhxuBLTrlhVUyxSPUKUV8r/2EI4ngqJxD7iBdBYLhwluN30JaT3Q==
LD_LIBRARY_PATH=/home/ali/aws-sdk-cpp/build/aws-cpp-sdk-s3:/home/ali/aws-sdk-cpp/build/aws-cpp-sdk-core ./s3client -e http://localhost:8000

For Go client:
# install "golang" package 
sudo dnf install golang #or apt-get install golang or something similar
export AWS_ACCESS_KEY_ID=0555b35654ad1656d804 \
AWS_SECRET_ACCESS_KEY=h7GhxuBLTrlhVUyxSPUKUV8r/2EI4ngqJxD7iBdBYLhwluN30JaT3Q==
export GOPATH=$HOME/go
go get -u github.com/aws/aws-sdk-go
export MY_ENDPOINT={ip address}:8000
go run simple_client.go #this will list buckets created with the cpp client


