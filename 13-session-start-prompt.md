# Session Start Prompt

Use this prompt at the beginning of a new work session to quickly catch up on the project's status and plan your work effectively.

## Purpose
Ensure continuity and awareness of project progress after breaks, and set a clear direction for the upcoming work session.

## Steps

1. **Review Recent Progress**:
   - Use the [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt) to get an overview of recent project updates.

2. **Check Recent Commits**:
   - Run `git log -n 5 --oneline` to see recent changes.
   - Note any significant updates or changes that might affect your work.

3. **Read Open Issues or Pull Requests** (if applicable):
   - Check the project's issue tracker or PR list.
   - Identify any urgent matters that require immediate attention.

4. **Assess Current Priorities**:
   - Determine if priorities have shifted since the last session.
   - Consider any new information from steps 1-3 that might impact priorities.

5. **Plan Your Work**:
   - Use the [Next Action Prompt](#8-next-action-prompt) to decide on tasks for the session.
   - Ensure your planned tasks align with the current project priorities and recent updates.

6. **Prepare the Development Environment**:
   - Open necessary files and tools.
   - Set up your workspace based on the tasks identified in step 5.

7. **Communicate Availability**:
   - Let the team know you're back and ready to work.
   - Share your planned focus for the session if appropriate.

## Benefits
- Saves time by avoiding unnecessary context switching.
- Ensures you start work with a clear understanding of what needs to be done.
- Helps maintain project momentum across multiple work sessions.

## Related Prompts
- [Progress Reader and Update Prompt](#9-progress-reader-and-update-prompt): Use this to review and update project progress.
- [Next Action Prompt](#8-next-action-prompt): Use this to determine the most appropriate tasks to work on.
- [Git Workflow Prompt](#7-git-workflow-prompt): Reference this if you need to perform any Git operations during your session.

## Remember
Always start your session by getting a comprehensive overview of the project status to ensure your work is aligned with the team's goals and recent developments.