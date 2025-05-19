# CSE110 Lab 7

1. Where would you fit your automated tests in your Recipe project development pipeline?
`ANSWER: Within a Github action that runs whenever code is pushed.` 
<br>
Running automated tests on every push ensures that any code that is pushed to Github will be validated. This helps prevent broken code from being pushed or merged, as well as maintaining overall code quality. Manually running the tests before pushing code takes too much time and is unnecesary. Running the test after development would be inefficient, as it would make it much harder to catch errors/bugs since broken code can be pushed or merged.

2. Would you use an end to end test to check if a function is returning the correct output?
`No, you wouldn't use an end to end test to check if a function is returning the correct output.`
<br>
To check if a functin is returning the correct output, you should use a unit test rather than an end ot end test. Unit tests are used to test individual functions or components in isolation. End to end tests are used to test the application as a whole to ensure that all of the functions and components work seamlessly. 