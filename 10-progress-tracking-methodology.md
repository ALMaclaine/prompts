# Progress Tracking Methodology

This document outlines how to effectively use `progress.json` to track project progress while maintaining alignment with the project plan located in the plans directory.

## Purpose
Ensure transparent and accurate tracking of project tasks and phases, while keeping the project aligned with its overall goals and timeline as defined in the project plan.

## Methodology

1. **Project Plan Alignment**:
   - Always refer to the project plan in the plans directory when updating progress to ensure consistency with project goals and timelines.
   - Any deviations from the plan should be noted and justified in progress updates.

2. **Consistent Updates**:
   - Update `progress.json` immediately after starting or completing a task.
   - Ensure updates reflect the current state of the project as outlined in the project plan.

3. **Clear Status Indicators**:
   - Use `"pending"`, `"in_progress"`, and `"completed"` to reflect task status.
   - Ensure these statuses accurately represent the task's state in relation to the project plan.

4. **Detailed Descriptions**:
   - Provide enough detail in task descriptions for clarity.
   - Reference specific sections or milestones from the project plan when applicable.

5. **Regular Reviews**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) at the start of each session.
   - Cross-reference progress with the project plan during these reviews.

6. **Version Control**:
   - Commit changes to `progress.json` with descriptive messages.
   - Include references to the project plan in commit messages when relevant.

7. **Communication**:
   - Discuss progress updates in team meetings or through project management tools.
   - Highlight any discrepancies between current progress and the project plan.

8. **Milestone Tracking**:
   - Clearly mark the completion of major milestones as defined in the project plan.
   - Update the project plan if milestone completion dates differ from the original timeline.

9. **Adaptive Planning**:
   - Use progress data to inform potential updates to the project plan.
   - Document any changes to the plan that result from progress insights.

## Benefits

- **Transparency**: Everyone stays informed about the project's status and its alignment with the overall plan.
- **Accountability**: Clear tracking of responsibilities and their relation to project goals.
- **Efficiency**: Easier identification of next actions based on the project plan and current progress.
- **Adaptability**: Ability to quickly identify and address deviations from the project plan.

## Example `progress.json` Structure
```json
{
  "current_phase": "User Authentication",
  "phases": [
    {
      "name": "User Authentication",
      "status": "in_progress",
      "plan_reference": "Section 2.1 in project plan",
      "steps": [
        {
          "description": "Design login UI",
          "status": "completed",
          "plan_milestone": "UI Design Completion"
        },
        {
          "description": "Implement password encryption",
          "status": "completed"
        },
        {
          "description": "Integrate OAuth providers",
          "status": "pending",
          "plan_deadline": "2023-07-15"
        }
      ]
    }
  ]
}
```

## Remember
- Keeping progress tracking accurate and aligned with the project plan benefits the entire team and ensures project success.
- Regular cross-referencing between `progress.json` and the project plan is crucial for maintaining project coherence.
- Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) and [Next Action Prompt](#8-next-action-prompt) in conjunction with this methodology for comprehensive project management.

## Related Prompts
- [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt)
- [Next Action Prompt](#8-next-action-prompt)
- [Documentation Prompt](#5-documentation-prompt) (for updating the project plan)
- [Code Implementation Prompt](#1-code-implementation-prompt) (for ensuring code changes align with the plan and progress)