# Next Action Prompt

Use this prompt to determine the next steps in the project based on current progress and the project plan.

## Purpose
Ensure continuous and efficient progress by identifying and prioritizing tasks that align with the project's overall objectives and timeline.

## Steps

1. **Review the Project Plan**:
   - Consult the project plan in the plans directory.
   - Understand the current phase of the project and upcoming milestones.

2. **Review Current Progress**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) to assess where the project stands in relation to the plan.

3. **Identify Pending Tasks**:
   - Look for pending steps in the current phase as outlined in the project plan.
   - Prioritize tasks based on importance, dependencies, and alignment with project goals.

4. **Select the Next Task**:
   - Choose the highest priority task that you're ready to tackle.
   - Ensure the selected task contributes directly to the project's objectives as defined in the plan.

5. **Determine the Appropriate Prompt**:
   - **Coding Task**: Use the [Code Implementation Prompt](#1-code-implementation-prompt).
   - **Testing Task**: Use the [Testing Prompt](#14-testing-prompt).
   - **Documentation Task**: Use the [Documentation Prompt](#5-documentation-prompt).
   - **Error Resolution**: Use the [Error Handling and Troubleshooting Prompt](#6-error-handling-and-troubleshooting-prompt).
   - **Code Review**: Use the [Code Review and Refactoring Prompt](#2-code-review-and-refactoring-prompt).

6. **Create a New Branch** (if applicable):
   - Follow the [Git Workflow Prompt](#7-git-workflow-prompt).
   - Ensure the branch name reflects the task and its relation to the project plan.

7. **Update Progress Tracking**:
   - Mark the task as "in_progress" in `progress.json`.
   - Update any relevant project management tools to reflect the current focus.

8. **Proceed with the Task**:
   - Follow the steps outlined in the relevant prompt.
   - Keep the project plan in mind throughout the task execution.

9. **Review and Adjust**:
   - After completing the task, reassess the project status against the plan.
   - Update `progress.json` and the project plan (if necessary) to reflect the completed work.
   - Identify any deviations from the plan and adjust future tasks accordingly.

10. **Plan for the Next Iteration**:
    - Based on the updated progress and project plan, prepare for the next iteration of tasks.
    - Identify any potential blockers or risks for upcoming tasks and plan mitigation strategies.

## Tips
- Regularly revisit this prompt and the project plan to stay aligned with project goals.
- Communicate with the team if priorities shift or if you identify any discrepancies between progress and the project plan.
- Use this prompt as an opportunity to reflect on the project's overall direction and suggest improvements to the plan if necessary.

## Related Prompts
- [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt)
- [Code Implementation Prompt](#1-code-implementation-prompt)
- [Testing Prompt](#14-testing-prompt)
- [Documentation Prompt](#5-documentation-prompt)
- [Error Handling and Troubleshooting Prompt](#6-error-handling-and-troubleshooting-prompt)
- [Code Review and Refactoring Prompt](#2-code-review-and-refactoring-prompt)
- [Git Workflow Prompt](#7-git-workflow-prompt)

Remember: The project plan is your north star. Every action taken should contribute to the realization of the project's vision and objectives as outlined in the plan. Use this prompt to ensure that each step you take is purposeful and aligned with the broader goals of the project.