# Test Driven Development

#### Test Driven Development is a software development method that interlaces unit testing, programming and refactoring.

Why is TDD important?
  * Provides feedback that the software is still working
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

What you should test
  * Unit tests work best for pure functions, function which
    1. Given the same input it will always return same output
    2. Doesn't have any side-effects like mutate shared state
  * API routes in the server
  *