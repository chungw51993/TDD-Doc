# Test Driven Development

#### Test Driven Development is a software development method that interlaces unit testing, programming and refactoring. It's one way to think through your requirements or design. The goal of TDD is to make you think about how your functions are going to act and write clean code.

Why is TDD important?
  * Provides feedback that the functions are still working properly
  * Reduces the number of bugs in your program
  * Forces you to slow down and think
  * Encourages you to refactor your code
  * Speeds up development by eliminating time wasted trying to debug
  * Gets rid of fear that app will break when you're adding new feature
  * It can make coding more fun

Steps to TDD:
1. Write one failing test
2. Implement the code to pass the test
3. Watch the test pass
4. Refactor - if necessary
5. Repeat

#### What is Unit Test?

**Unit test is a software testing where individual functions/units of a software are tested**

  * It is the first level of testing
  * It is usually for developers to check if they are breaking any function while developing
  * The purpose is to validate that each unit of the software is working properly

**What to Unit Test**
  * Test single function - test should be simple, quick to write and quick to run.
  * Unit tests work best for pure functions, function which
    1. Given the same input it will always return same output
    1. Doesn't have any side-effects like mutate shared state
  * They should be isolated from dependencies - no network access and database access
  * Test API routes in the server
  * Test Database controller

**Things to Keep in Mind**
  * Be sure to isolate the development environment from the test environment
  * Use test data that is close to the production data
  * Write test cases that are independent from other tests

**Some of the test suites**
  * Karma - Can't use it to test backend because it's only for browser-based code (AngularJS)
  * Mocha - Can be used for backend and frontend
  * Jest - Can be used for backend and frontend (React)
  * Sinon - Can be used for spies, stubs, and mocks with any test framework

**Difference between TDD and BDD**

**Test-Driven Development** consists of unit tests that are testing if a single modular function is working properly.

**Behavior-Drive Development** consists of tests that are testing if functions will work properly to the behavior(ex. user input, timer).