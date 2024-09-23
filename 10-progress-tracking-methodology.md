# Progress Tracking Methodology

This document outlines how to effectively use `progress.json` to track project progress.

## Purpose
Ensure transparent and accurate tracking of project tasks and phases.

## Methodology

1. **Consistent Updates**:
   - Update `progress.json` immediately after starting or completing a task.

2. **Clear Status Indicators**:
   - Use `"pending"`, `"in_progress"`, and `"completed"` to reflect task status.

3. **Detailed Descriptions**:
   - Provide enough detail in task descriptions for clarity.

4. **Regular Reviews**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) at the start of each session.

5. **Version Control**:
   - Commit changes to `progress.json` with descriptive messages.

6. **Communication**:
   - Discuss progress updates in team meetings or through project management tools.

## Benefits

- **Transparency**: Everyone stays informed.
- **Accountability**: Clear tracking of responsibilities.
- **Efficiency**: Easier identification of next actions.

## Example `progress.json` Structure
```json
{
  "current_phase": "Phase Name",
  "phases": [
    {
      "name": "Phase Name",
      "status": "in_progress",
      "steps": [
        {
          "description": "Task Description",
          "status": "completed"
        },
        {
          "description": "Next Task",
          "status": "pending"
        }
      ]
    }
  ]
}
```

## Remember
Keeping progress tracking accurate benefits the entire team and project success.