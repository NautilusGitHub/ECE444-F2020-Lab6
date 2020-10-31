# ECE444-F2020-Lab6
Using material from: https://github.com/mjhea0/flaskr-tdd

Q: Pros and Cons of TDD:
A: Test driven development (TDD) is one style of programming that exists, where requirements involve test cases, and the code is developed to meet these test cases. 
It is an iterative way to improve upon code, and often has a short development style and fewer bugs due to every new feature being tested upon inclusion. 
The main benefit of this development style is the high confidence and design structure of this method, and the fact that it can help remove bugs. 
The new tests themselves are first run without anything added, to ensure that they fail and that the feature isn’t already implemented. 
This helps ensure that the test is valid and doesn’t produce wrong results, increasing confidence in the test. 
By writing code to try and pass these tests, the programmer is simultaneously adding new features and testing the results, since once the features are implemented, the tests are run again to ensure they now pass. 
Cleanup and refactoring is also done between cycles to prevent the code from being too cluttered and haphazard, and the tests can be re-run to ensure no functionality is lost. 
The end result is code that has been unit tested as it has been implemented, which helps reduce the change of bugs appearing.  

However, TDD also has major drawbacks. 
It is quite time consuming to do, and adds extra complexity, as you now have to implement many new tests each time a new feature is implemented. 
The tests also have to be redone every time an old feature is changed or removed, which is also additional work that needs to be done. 
So, if the code is expected to change greatly and evolve over the course of development, TDD may not be the most viable style to use. 
As well, the unit testing and code structure must be done well, and encompass all the potential behaviour of the feature, otherwise errors can still pop up even with all the added hassle of developing tests.  

In the end, TDD is a style of programming that comes with its pros and cons, just like every style. Therefore, one must weigh the pros and cons of it and consider whether it is appropriate for the task at hand, rather than blindly applying it to everything.
