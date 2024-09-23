# Testing Prompt

Use this prompt when creating and executing tests to validate code functionality.

## Purpose
Ensure that all code changes are properly tested to maintain code quality.

## Steps

1. **Identify What to Test**:
   - Determine the functionalities, classes, or methods that need testing.

2. **Choose the Type of Tests**:
   - **Unit Tests**: Test individual components.
   - **Integration Tests**: Test interactions between components.
   - **End-to-End Tests**: Test the application flow from start to finish.
   - **Performance Tests**: Assess speed and responsiveness.

3. **Set Up the Testing Environment**:
   - Configure testing frameworks (e.g., Jest, Mocha).
   - Ensure all dependencies are installed.

4. **Write Test Cases**:
   - Follow best practices for writing tests.
   - Cover both typical use cases and edge cases.
   - Ensure tests are independent and repeatable.

5. **Run Tests**:
   - Execute tests using the appropriate commands.
   - Example: `npm test`

6. **Analyze Results**:
   - Review test outcomes.
   - Debug and fix any failing tests.

7. **Review Test Coverage**:
   - Use tools to assess code coverage.
   - Aim for high coverage but prioritize meaningful tests.

8. **Document Tests**:
   - Comment on complex test logic.
   - Update any test-related documentation.

9. **Integrate Tests into CI/CD Pipeline** (if applicable):
   - Ensure tests run automatically during builds.

10. **Commit Test Code**:
    - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt).

## Tips
- Write tests alongside or before implementing code (Test-Driven Development).
- Keep tests up to date with code changes.