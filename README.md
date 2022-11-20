# ECE444-F2022-Lab6

## Link to heroku app
https://secret-river-25542.herokuapp.com/

## Test cases added to group project
https://github.com/camillebruckmann/ECE444-Group4-EP/blob/camille-tests/Education_Pathways/tests/test_app.py#L33-L70

## What are the pros and cons of TDD?

Test-driven development (TDD) is a programming technique where code is written based on tests. That is, before writing code for a particular feature, the tests are written first to guide the feature implementation. A couple advantages of TDD include modularity, easy maintenance, and less unnecessary code. TDD provides modularity because it divides each feature by its own set of tests. As a result of this, it is easy to maintain because adding more tests to a feature or improving said feature will not influence others, since they are decoupled. Lastly, TDD results in the production of less unnecessary code as the code written is guided by the test cases, which outlines the requirements for the feature. 

Despite its advantages, TDD also has a few disadvantages. First of all, TDD is a great way to catch bugs but by no means is it a silver bullet. Other bugs created during the implementation or even in the test cases will need careful attention, as TDD may not catch them. TDD is also a slower process, requiring a significant amount of planning before developing the feature. Lastly, TDD needs the cooperation of everyone on the team. If some developers choose not to write unit tests for their feature, the requirements for the feature can easily get lost and cause confusion among the rest of the team.
