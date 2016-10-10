# antlr4ts
TypeScript/JavaScript target for ANTLR 4

## Dev setup with Visual Studio
Any edition of [Visual Studio 2015](https://www.visualstudio.com/vs/) (or greater) should work, including Communitity Edition.
You'll want to be sure you have the following VS extensions installed:
- [Node Tools for Visual Studio 1.2](https://www.visualstudio.com/vs/node-js/) (or greater)
- [TypeScript for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48593) 2.03 or greater.

You ***should*** be able to run tests from the Test Explorer, etc... but there seems to be an unresolved problem making this work, for now use the command-line method below to be sure you run them all.

## Dev setup with NPM
Of course, you'll need to install Node.js for your platform.   https://nodejs.org/en/
After cloning the repository, you can install dependencies by changing into the cloned directory and typing:

```
npm Install
```
you will need to do this again as we take on new dependencies or updates. 

### Running basic tests should be as simple as...
```
npm Test
```
How we integrate with runtime-testsuite is TBD.

### Generating test code coverage report
```
npm run cover 
```
This executes a code-coverage test run, then generates an interactive HTML report in `coverage/lcov-report/index.html`.
