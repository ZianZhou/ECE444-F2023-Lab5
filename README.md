# ECE444-F2023-Lab5

### Disclaimer

The code found in this repo is taken from the open source project: https://github.com/mjhea0/flaskr-tdd

### What are the pros and cons of TDD?

Regarding the pros, test-driven development can improve the quality of the code itself. If developers can code based on the tests that are already written, they will know what the expected output should be based on the provided input, and develop with better coding practices. There will be less bugs as a result. It will also be easier to debug in case there is a bug, as the developer can simply run the tests and compare the expected output against the actual output. Furthermore, in the long run, TDD will provide a much more maintainable codebase as the entire project is broken into smaller separate components, which can be worked on individually.

In terms of the cons, there will be potentially more development work required to code like this. There is an initial overhead of having to actually write the tests beforehand, and spending too much time on this component will result in no tangible progress in the actual project. If the developers are inexperienced with TDD, they might spend too much time on this due to the steep learning curve and may even write incomplete test coverage. This will lead to huge loopholes in the project that can lead to bugs later on in the development stage. TDD will also cause headaches for developers whenever they want to make a change to the codebase. Not only will they have to rewrite the feature code with the tests in mind, but they will also have to refactor the tests themselves to integrate with the new changes.
