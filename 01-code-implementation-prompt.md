# Code Implementation Prompt

Use this prompt when implementing new features, creating new files, or modifying existing ones.

## Purpose
Guide the process of coding new functionalities or updating existing ones, ensuring consistency, quality, and alignment with the project plan.

## Steps

1. **Review the Project Plan**:
   - Consult the project plan in the plans directory.
   - Identify the specific feature or functionality you're implementing within the plan's context.
   - Understand how this task fits into the overall project objectives and timeline.

2. **Define the Task**:
   - Clearly state the feature or functionality to implement.
   - Specify requirements and acceptance criteria, ensuring they align with the project plan.

3. **Plan the Implementation**:
   - **New File**:
     - Determine the file name and location, considering the project structure outlined in the plan.
     - Explain the file's purpose and role in the project, referencing relevant sections of the plan.
   - **Existing File**:
     - Identify the file and its location.
     - Describe the changes and reasons, linking them to specific goals or milestones in the project plan.
   - Outline main components or functions, ensuring they align with the planned architecture and design principles.
   - List dependencies or imports needed, verifying they're consistent with the technology stack specified in the plan.

4. **Write the Code**:
   - Follow coding standards and best practices as outlined in the project plan.
   - Use clear and descriptive names that reflect the project's naming conventions.
   - Include comments for complex logic, referencing relevant parts of the project plan if necessary.
   - Ensure error handling and consider edge cases. (For detailed guidance, refer to the [Error Handling and Troubleshooting Prompt](#6-error-handling-and-troubleshooting-prompt))
   - Keep the code modular and maintainable, adhering to the architectural principles defined in the plan.

5. **Write Tests**:
   - Develop unit tests alongside the code, ensuring coverage of requirements specified in the project plan.
   - Cover main functionality and edge cases.
   - Ensure all tests pass before proceeding.

6. **Update Documentation**:
   - Document new features or changes, maintaining consistency with the project's documentation standards.
   - Update any relevant user guides or API docs.
   - Ensure the documentation reflects the current state of the project as per the plan.

7. **Review and Refine**:
   - Self-review the code for any improvements, checking alignment with the project plan.
   - Refactor if necessary for better clarity or performance, always considering the project's goals and constraints.
   - Consider using the [Code Review and Refactoring Prompt](#2-code-review-and-refactoring-prompt) for a more thorough review.

8. **Update Progress**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) to update the project's progress tracking.
   - Ensure that the completed task is properly reflected in the project's progress metrics.

9. **Proceed to Commit**:
   - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt) to craft your commit message, referencing relevant aspects of the project plan.
   - Follow the [Git Workflow Prompt](#7-git-workflow-prompt) for guidance on branching and merging your changes.

10. **Plan Next Steps**:
    - Consult the [Next Action Prompt](#8-next-action-prompt) to determine the next task in alignment with the project plan.

## Related Prompts
- [Code Review and Refactoring Prompt](#2-code-review-and-refactoring-prompt)
- [Error Handling and Troubleshooting Prompt](#6-error-handling-and-troubleshooting-prompt)
- [Git Workflow Prompt](#7-git-workflow-prompt)
- [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt)
- [Next Action Prompt](#8-next-action-prompt)

Remember: Always keep the project plan in mind throughout the implementation process. It serves as the guiding document for all development activities, ensuring that each code change contributes meaningfully to the project's overall goals and vision.