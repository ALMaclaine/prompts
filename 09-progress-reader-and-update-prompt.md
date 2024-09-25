# Progress Reader and Update Prompt

Use this prompt to analyze and update the project's progress using `progress.json`, while ensuring alignment with the project plan in the plans directory. For a comprehensive understanding of the progress tracking system, refer to the [Progress Tracking Methodology](#10-progress-tracking-methodology).

## Purpose
Keep track of the project's current status, ensure everyone is informed about ongoing and completed tasks, and maintain alignment with the project plan.

## Steps

### Reading Progress

1. **Review the Project Plan**:
   - Open and review the project plan in the plans directory to understand the overall project structure and goals.

2. **Open `progress.json`**:
   - Locate the file in the project directory.

3. **Identify the Current Phase**:
   - Look for the `"current_phase"` field.
   - Cross-reference with the project plan to ensure the phase aligns with the planned timeline.

4. **List Completed and Pending Steps**:
   - Under the current phase, note which steps are marked as `"completed"`, `"in_progress"`, or `"pending"`.
   - Verify that these steps correspond to the tasks outlined in the project plan for the current phase.

5. **Summarize the Project Status**:
   - Prepare a brief overview:
     ```
     Current Phase: [Phase Name] ([Status])
     Completed Steps: [List of steps]
     Next Pending Step: [Description]
     Alignment with Project Plan: [Any discrepancies or notes]
     ```

### Updating Progress

1. **Update Step Status**:
   - Change the status of completed tasks to `"completed"`.
   - Mark new tasks as `"in_progress"` if starting them.
   - Ensure all updates are in line with the project plan and timeline.
   - Follow the [Progress Tracking Methodology](#10-progress-tracking-methodology) for consistent updates.

2. **Add New Tasks or Phases** (if necessary):
   - Ensure they are correctly nested within the JSON structure.
   - Verify that new tasks or phases are consistent with the project plan.
   - If adding elements not originally in the plan, note the reasons and potential impacts.

3. **Check for Milestone Completion**:
   - Review if any project milestones have been reached.
   - Update the project plan if necessary to reflect significant progress or changes.

4. **Save Changes**:
   - Ensure the JSON syntax is valid.
   - Double-check that all updates are consistent with the project plan.

5. **Commit Progress Updates**:
   - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt).
   - Include references to the project plan in the commit message if relevant.

6. **Update Project Plan** (if necessary):
   - If progress reveals the need for adjustments to the project plan, note these for discussion.
   - Use the [Documentation Prompt](#5-documentation-prompt) to update the project plan if changes are approved.

7. **Communicate Changes**:
   - Inform the team of significant updates, especially those that impact the project timeline or goals.
   - Highlight any deviations from the original plan and explain the reasons.

## Example Summary
```
Current Phase: User Authentication (in_progress)
Completed Steps: 
- Design login UI
- Implement password encryption

Next Pending Step:
- Integrate OAuth providers

Alignment with Project Plan:
- On track with timeline
- Added additional security feature (2FA), may impact next phase start date
```

## Tips
- Keep `progress.json` up to date to avoid confusion and ensure accurate project tracking.
- Use this prompt at the start and end of work sessions to maintain consistent progress updates.
- Regularly review the [Progress Tracking Methodology](#10-progress-tracking-methodology) and the project plan to ensure consistent tracking across the project.
- Use this prompt as an opportunity to reflect on the project's overall direction and suggest improvements to the plan if necessary.

## Related Prompts
- [Progress Tracking Methodology](#10-progress-tracking-methodology): Refer to this for a detailed explanation of the progress tracking system.
- [Commit Message Generation Prompt](#3-commit-message-generation-prompt): Use this when committing progress updates.
- [Documentation Prompt](#5-documentation-prompt): Use this when updates to the project plan are necessary.
- [Next Action Prompt](#8-next-action-prompt): Consult this to determine the next steps based on the current progress.

Remember: The project plan and `progress.json` should always be in sync. Any discrepancies between the two should be addressed promptly to ensure the entire team is working towards the same goals and timeline.