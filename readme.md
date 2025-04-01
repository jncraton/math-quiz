Math Quiz
=========

A math quiz application in Python.

Learning Objectives
-------------------

After completing this lab, students will be able to:

- Create tests for object oriented Python code
- Use `unittest` to create, discover, and run tests
- Mock objects to properly isolate tests

Task
----

The handout code provided in [mathquiz.py](mathquiz.py) will allow a user to complete a simple math quiz when executed. The code is missing tests. Use the [unittest](https://docs.python.org/3/library/unittest.html) module to verify the following:

1. AdditionProblem returns the correct solution
2. SubtractionProblem returns the correct solution
3. Confirm that CLIAnswerChecker produces the correct output when correct solutions are provided
4. MathQuiz `score` is correct

Resources
---------

It may be necessary to mock certain methods (random.randint, input, print, etc) in order to test functionality reproducibly. It is recommended to use [unittest.mock](https://docs.python.org/dev/library/unittest.mock.html) for this purpose.
