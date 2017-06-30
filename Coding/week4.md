**Serious refactoring and tests on bucket and object operations**

From feedback on last week's tests, I did alot of refactoring and wrote more tests

**Achievements**

+ Mentor was able to execute the tests using the instructions in the project readme.
+ I have written up to 80 tests.
+ I have been doing alot of refactoring from feedback i got especially on teardowns and ensuring each tests has its own independent procedure. I decided to change to testify/suite from  testify/assert so that I can make use of its test setup and teardown features. Bucket names were also refactored to be random so that each test works withits own unique bucket. 
+ I was also able to reach  the [author](https://github.com/robbat2) of an [issue](https://github.com/nanjekyejoannah/go_s3tests/issues/1) on the project for details but also guidance on how to handle the issue.


**Tasks for the Next Week**

+ Implement tests on SSE and host styles.
+ Ensure Mentor is able to run tests.