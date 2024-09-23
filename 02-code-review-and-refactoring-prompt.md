# Code Review and Refactoring Prompt

Use this prompt when reviewing existing code or considering refactoring opportunities.

## Purpose
Improve code quality, maintainability, and performance by systematically reviewing and refining the codebase.

## Steps

1. **Select the Code to Review**:
   - Identify files or components needing review.

2. **Analyze the Code**:
   - **Functionality**: Verify correct implementation.
   - **Readability**: Check for clear and understandable code.
   - **Efficiency**: Look for performance issues.
   - **Maintainability**: Assess modularity and extensibility.
   - **Error Handling**: Ensure all cases are properly managed.
   - **Consistency**: Confirm adherence to coding standards.

3. **Identify Issues and Opportunities**:
   - Note code smells or anti-patterns.
   - Document any redundant or obsolete code.

4. **Plan Refactoring**:
   - Prioritize issues based on impact.
   - Choose appropriate refactoring techniques:
     - Extract Method
     - Rename Variable/Function
     - Simplify Conditionals
     - Reduce Complexity

5. **Implement Refactoring**:
   - Make incremental changes.
   - Test after each change to ensure functionality remains intact.

6. **Update Tests**:
   - Modify existing tests if necessary.
   - Add new tests to cover refactored code.

7. **Document Changes**:
   - Update comments and documentation.
   - Record the rationale for significant changes.

8. **Commit Changes**:
   - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt) for commit messages.
   - Follow the [Git Workflow Prompt](#7-git-workflow-prompt) for branching and merging.

9. **Communicate**:
   - If changes affect others, communicate with the team.
   - Schedule code reviews if needed.

## Remember
The goal is to enhance the code without altering external behavior.