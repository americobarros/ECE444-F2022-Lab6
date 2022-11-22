This repo is a copy the original tutorial which can be located [here](https://github.com/mjhea0/flaskr-tdd)
## Comments from the group file
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-5-io/blob/main/Education_Pathways/tests/test_app.py#L311-L365
## Pros and Cons of TDD
### Pros
 - Maintenence and refactoring is much more simple, since tests are written for specific coverage, then refactoring code or fixing a failing postion of code, it is much more simple and straighforward to see what part of the code is functioning or not funcitioning and what needs to be changed.
 - Since code is developed along side the tests, it will typically result in a very high text coverage of the code, allowing for a more secure and less error prone application.
 - Features can be developed in a more mudular way. When writing a test, you can test a specific part of the application. Once the tests pass, then that specific module could be marked as completed, making it easier to create modules.
## Cons
 - Maintenence is another issue with TDD. Having tests that will tell you when something is wrong is fantastic except when the tests themselves are wrong. This could be due to a change to the application code or removal of features, but failing tests which are false positives  take time to diagnose and fix.
 - Slower development process can be one of the downfalls of TDD. Creating and writing smart tests take time on their own, and this is on top of the applicaiton code that must be written in order to pass the tests afterwards. Becuase of this extra layer of complication, there are times that TDD can make the process more complicated and time consuming.

