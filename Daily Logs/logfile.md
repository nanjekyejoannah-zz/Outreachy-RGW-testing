
## Coding Period

We started off the coding period on 30th May. The [week 1](https://github.com/nanjekyejoannah/go_s3tests/blob/master/Community%20Bonding/week1.md) has more updates. The daily log is not so up to date. I want to save some time for other interesting things than updating what I had missed in daily logs. After all the week 1 summary does a good job.

### 7th, June, 2017

#### Hacked RGW connection

**Tasks Accomplished**

+ I hacked connection to RGW from one machine to another using Go client. 
+ I began writing tests for [s3 bucket operations](https://trello.com/b/etwTtnv4/outreachy-rgw-testing)

**Tasks for the next period**

+ Commit tests on bucket operations for feedback.
+ Discuss an [issue](https://github.com/nanjekyejoannah/go_s3tests/issues/1) opened with author.


### 6th, June, 2017

#### Got feedback from tests, Discussed RGW connection

**Tasks Accomplished**

+ I had chat with mentor discussing how I can goabout connection. 
+ I got feedback on the eight tests I had commited

**Tasks for the next period**

+ Connect to RGW with Go



### 5th, June, 2017

#### Submitted First Tests for Feedback, Hacking connection to RGW.

**Tasks Accomplished**

+ I worked on my first tests and submitted them for feedback. 
+ I embacked on hacking the RGW Connection.
+ I also  did some house keeping things like blogging what I have learned, updating the project tracker and Trello boards.

**Tasks for the next period**

+ Connect to RGW

**Blockers**

+ Having a few hickups with my machine hanging when I run Ceph. It will work for the most time. However it hangs often and it is inconviniencing. I am considering another plan of running ceph on another computer and just using my laptop to connect to RGW.



## Community Bonding


### 13th, May, 2017

#### Prepare Week Activity log, Run python RGW tests.

**Tasks Accomplished**

+ Created [Project Tracker]((https://github.com/Outreachy-RGW-testing)) on github. 
+ Created and update Trello Board.
+ Examined the RGW [python test Suite](https://github.com/ceph/s3-tests) codebase to get an idea on what tests to write for the other language suites.

**Tasks for the next period**

+ Have IRC with mentor to discuss project execution and my questions on ceph workflow.
+ Run those tests in python Suite on fedora.


### 12th, May, 2017

#### Solved Fedora Blockers and Run RGW tests in python Suite.

**Tasks Accomplished**

+ Built the vstart target and ran it finally. 
+ Examined the RGW [python test Suite](https://github.com/ceph/s3-tests) to get an idea on how to connect to RGW and general architecture.

**Tasks for the next period**

+ Create Project Tracker.
+ Run the tests on the RGW [python test Suite](https://github.com/ceph/s3-tests)on the setup fedora environment.
+ Dig into the the RGW [python test Suite](https://github.com/ceph/s3-tests) codebase for ideas to get an idea on what tests to write for the other language suites.


### 11th, May, 2017

#### Setup Dev Environment to Fedora not Ubuntu

**Tasked Accomplished**

+ I setup a Fedora Virtual Machine and installed GO, C++ and Java AWS SDKs. This is all I did with abit of hickups as It was my first time working with Fedora.
+ Cloned Ceph to Build the vstart target and run it.
+ I ran into a few blockers building the vstart target and will look into tommorrow

**Taskes for the next period**

+ Build the vstart target and run it.


### 10th, May, 2017

#### Running the tests from the python Suite

**Tasked Accomplished**

+ Cloned the RGW [python test Suite](https://github.com/ceph/s3-tests).
+ Ran Tests from the Suite using Ubuntu.


### 9th, May, 2017

#### Installing the AWS SDKs

**Tasked Accomplished**

+ I Setup an Ubuntu Virtual machine and installed GO, C++ and Java AWS SDKs.
+ Cloned Ceph, Built the the vstart target and ran it.
+ Read up on AWS SDK for C++ Developer Guide.

**Tasks for the next period**

+ Clone and run the RGW  python Test Suite.
+ Make sense of the code


### 8th, May, 2017

#### A day full of reading and code kataring.

**Tasked Accomplished**

+ Project Mentor Introduced me to the ceph community.
+ Read up C++ programming concepts and creating make files.
+ Read up concepts on Google test.


**Tasks for the next period**

+ Setup Ubuntu Virtual machine and install AWS SDKs.
+ Clone Ceph, Build the vstart target and run it.
+ Read about AWS SDK for C++ Developer Guide.
