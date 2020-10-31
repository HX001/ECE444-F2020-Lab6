# ECE444-F2020-Lab6

## Part 1: Replay the example
- This repo is a replay of the example of https://github.com/mjhea0/flaskr-tdd

## Part 2: Test Cases 
Here is the url of the test function I added to our group project:
- https://github.com/ECE444-2020Fall/project1-webapp-group1-nightowls/blob/FrontEnd_Hong/cookpilot-web/src/test/App.test.js#L24-L89

## Part 3: What are the pros and cons of TDD?
TDD, Test-Driven Development, is a software development methodology, that developer needs to run a set of tests before actually writing code. The idea is that the test cases will fail at the beginning, and the developer needs to write enough code to make each test case pass at the end. There is another way by doing test-driven development, the developer first writes the code for each module and then writes the test to the actual performance of the code. By doing this, the quality of the code can be measured. There are some pros and cons by doing TDD, they are listed below:

Pros:
1. By writing a small test at the early stage of the development may force the developer to focus on a specific module against the test cases. In a word, TDD helps the developer to learn, understand, and internalize the key principles of good modular design. Also, TDD helps the developer to clarify the purpose. Before the developer starts writing the production code, they must first think about the input and output and the corresponding logic behind it. Writing test cases helps the developer meets the requirements and increases the understanding of the requirements.

2. In order to make sure the production code is unit-testable, TDD forces the developer to design a good architecture, and the developed code is modulized corresponding to each test case.

3. TDD ensures the efficiency of the collaboration between the team members. The team member can edit the code written by others as long as the test case passed because unit tests allow the developer to know whether the changes are making the code behave in unexpected ways.

4. TDD saves developers time debugging since the unit test case allows the developer to get closer to the problem quickly.

5. TDD encourages small steps and improves the design because it helps the developer cut unnecessary dependencies to facilitate the setup.

6. TDD makes the developer organize the code more clearly. Testing while writing also forces you to try to make your interfaces clean enough to be tested


Cons:
1. TTD may increase the developer's work, and the tests may be hard to write, which slows down the development efficiency.

2. TDD may increase the difficulty of the development. It is hard to apply to existing legacy code.

3. TDD necessitates a lot of time and effort up front, which means the developer may take a longer time to do the prework and slow down the 
implementation process.

4. Sometimes, writing a good test is not an easy thing to do, especially it requires to cover the essentials and avoid the superfluous.

5. TDD may take a longer time and much more effort to maintain the unit test because it must be reconfigured for maximum value.

6. If the design changes rapidly, the developer will need to keep changing the tests. The developer may spend a lot of time writing tests for features that will be dropped later, which will also slow down the development efficiency.
