# ECE444-F2020_Lab6
This repo is a replay of the example of https://github.com/mjhea0/flaskr-tdd

## Add test cases to your group project
Here is the url of the function I added to my project:  

https://github.com/ECE444-2020Fall/project1-webapp-group1-nightowls/blob/Backend/tests/test_authentication.py#L22-L43

Here is a screenshot of the test case I created for the sign up function in the project:  

![alt text](image/Screenshot_5.jpg)

## What are the pros and cons of TDD
Test Driven Development is a software development appoach that each functionality has associated test cases attached to it to ensure it works as expected. If the test cases fail, then we need to modify the code or write new codes in order to pass the test cases. This process can be repeated if needed.

Here are some advantages of TDD:
* It helps the developers to catch trival bugs
* It allows the developers to catch bugs early
* It helps the developers to understand how each functionality works and will be used
* It allows the developers to know where the problem is so one can save time trying to identify the problem
* It forces the developers to write modular codes so that it is easier for testing, which makes the code more clean and easy to read
* It makes the code easier to maintain
* It makes the team collaboration easier. Because having the tests, it allows team members to know if the changes made will affect other parts of the project
* The developers only need to write the test for each functionality once and it can be tested multiple times
* It provides team members more confident to edit other's code

Here are some disadvantages of TDD:
* It may slow down the project development because the developers have to spend time writing tests for each functions they wrote
* It will be hard to write tests for any legacy code or some non-modular code
* As the size of the project increases, writing too many tests may increate the time to build the project
* It is difficult to write good tests
* If the design requirement is changing, then the developers need to change the tests as well
* Developers may write more tests for one function than it actually needs
* It is difficult for all team members to keep the habit of writing unit tests
