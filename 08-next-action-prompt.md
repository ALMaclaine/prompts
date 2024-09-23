# Next Action Prompt

Use this prompt to determine the next steps in the project based on current progress.

## Purpose
Ensure continuous and efficient progress by identifying and prioritizing tasks.

## Steps

1. **Review Current Progress**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) to assess where the project stands.

2. **Identify Pending Tasks**:
   - Look for pending steps in the current phase.
   - Prioritize tasks based on importance and dependencies.

3. **Select the Next Task**:
   - Choose the highest priority task that you're ready to tackle.

4. **Determine the Appropriate Prompt**:
   - **Coding Task**: Use the [Code Implementation Prompt](#1-code-implementation-prompt).
   - **Testing Task**: Use the [Testing Prompt](#14-testing-prompt).
   - **Documentation Task**: Use the [Documentation Prompt](#5-documentation-prompt).
   - **Error Resolution**: Use the [Error Handling and Troubleshooting Prompt](#6-error-handling-and-troubleshooting-prompt).

5. **Create a New Branch** (if applicable):
   - Follow the [Git Workflow Prompt](#7-git-workflow-prompt).

6. **Update Progress Tracking**:
   - Mark the task as "in_progress" in `progress.json`.

7. **Proceed with the Task**:
   - Follow the steps outlined in the relevant prompt.

8. **Review and Adjust**:
   - After completing the task, reassess the project status.
   - Update `progress.json` accordingly.

## Tips
- Regularly revisit this prompt to stay aligned with project goals.
- Communicate with the team if priorities shift.