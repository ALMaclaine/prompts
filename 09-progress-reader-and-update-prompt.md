# Progress Reader and Update Prompt

Use this prompt to analyze and update the project's progress using `progress.json`.

## Purpose
Keep track of the project's current status and ensure everyone is informed about ongoing and completed tasks.

## Steps

### Reading Progress

1. **Open `progress.json`**:
   - Locate the file in the project directory.

2. **Identify the Current Phase**:
   - Look for the `"current_phase"` field.

3. **List Completed and Pending Steps**:
   - Under the current phase, note which steps are marked as `"completed"`, `"in_progress"`, or `"pending"`.

4. **Summarize the Project Status**:
   - Prepare a brief overview:
     ```
     Current Phase: [Phase Name] ([Status])
     Completed Steps: [List of steps]
     Next Pending Step: [Description]
     ```

### Updating Progress

1. **Update Step Status**:
   - Change the status of completed tasks to `"completed"`.
   - Mark new tasks as `"in_progress"` if starting them.

2. **Add New Tasks or Phases** (if necessary):
   - Ensure they are correctly nested within the JSON structure.

3. **Save Changes**:
   - Ensure the JSON syntax is valid.

4. **Commit Progress Updates**:
   - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt).

5. **Communicate Changes**:
   - Inform the team of significant updates.

## Example Summary
```
Current Phase: User Authentication (in_progress)
Completed Steps: 
- Design login UI
- Implement password encryption

Next Pending Step:
- Integrate OAuth providers
```

## Tips
- Keep `progress.json` up to date to avoid confusion.
- Use this prompt at the start and end of work sessions.