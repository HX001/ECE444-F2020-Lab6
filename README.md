# ECE444-F2020-Lab6

## Part 1: Replay the example
- Source example: https://github.com/mjhea0/flaskr-tdd

## Part 2: Test Cases 
- https://github.com/ECE444-2020Fall/project1-webapp-group1-nightowls/blob/FrontEnd_Hong/cookpilot-web/src/test/App.test.js#L24-L89

## Part 3: What are the pros and cons of TDD?
TDD, Test-Driven Development, is a software development methodology, that developer needs to run a set of tests before actually writing code. The idea is that the test cases will fail at the beginning, and the developer needs to write enough code to make each test case pass at the end. There is another way by doing test-driven development, the developer first writes the code for each module and then writes the test to the actual performance of the code. By doing this, the quality of the code can be measured. There are some pros and cons by doing TDD, they are listed below:

Pros:
1. By wring a small test initially, it may force the developer to focus on specific module in order to against the test cases. In a word, TDD helps developer to  learn, understand, and internalize the key principles of good modular design. Also, TDD helps developer to clarify the purpose. Before developer start writing the production code, they must first think about the input and output and the corresponding logic behind it. Writing test cases that meet the requirements, and increase the understanding of the requirements.

2. In order to make sure the production code is unit-testable, TDD forces the developer to design a good architecture, and the developed code is modulized corresponding to each test case.

3. TDD ensures the efficiency of the collaboration between the team members. Team member can edit the code wrotten by others as long as the test case passed because the result of unit tests allow the developer know whether if the changes are making the code behave in unexpected ways.

4. TDD saves developers time on degbugging since the unit test case allows developer get closer to the problem quickly.

5. Also, TDD insure encourages small steps and improves the design because it help the developer to cut the unnecessary dependencies to facilitate the setup.

6. TDD makes the developer to organize the code more clearly.Testing while writing also forces you to try to make your interfaces clean enough to be tested


Cons:
1. TTD may increase the work to the developer, and the tests may be hard to write, which slow down the development efficiency.

2. TDD may increase the difficulty of the development. It is Hard to apply to existing legacy code.

3. It necessitates a lot of time and effort up front, which can make development feel slow to begin with.

4. Sometimes, writing a good test is not a easy thing to do, especially it requires to cover the essentials and avoid the superfluous.

5. It may take longer time and much more effort to maintain the unit test because it must be reconfigured for maximum value.

6. If the design changes rapidly, the developer will need to keep changing the tests. The developer may spend a lot of time to write tests for features that will be dropped later, which will also slow down the development efficiency.
