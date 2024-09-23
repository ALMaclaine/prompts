# Git Workflow Prompt

Use this prompt to guide the process of branching, committing, and merging code using Git.

## Purpose
Maintain an organized and efficient workflow when collaborating on code.

## Steps

1. **Start a New Feature Branch**:
   - Create and switch to a new branch:
     ```
     git checkout -b [branch-name]
     ```
   - Use descriptive branch names (e.g., `feature/user-authentication`).

2. **Develop Your Changes**:
   - Work on your code in this branch.
   - Commit changes frequently with meaningful messages.

3. **Stage and Commit Changes**:
   - Stage changes:
     ```
     git add [file-name]
     ```
   - Commit changes using the [Commit Message Generation Prompt](#3-commit-message-generation-prompt):
     ```
     git commit -m "Your commit message"
     ```

4. **Sync with Remote Repository** (if collaborating):
   - Pull the latest changes:
     ```
     git pull origin master
     ```
   - Resolve any merge conflicts.

5. **Push Your Branch**:
   - Push the branch to the remote repository:
     ```
     git push origin [branch-name]
     ```

6. **Create a Pull Request** (if using PR workflow):
   - Open a PR against the `master` branch.
   - Request reviews if necessary.

7. **Merge Changes into Master**:
   - After approval, merge your branch:
     ```
     git checkout master
     git merge [branch-name]
     ```
   - Delete the feature branch:
     ```
     git branch -d [branch-name]
     ```

8. **Push Master to Remote**:
   - Update the remote `master` branch:
     ```
     git push origin master
     ```

9. **Update Progress Tracking**:
   - Update `progress.json` if applicable.
   - Commit the progress update.

## Remember
- Keep your `master` branch clean and stable.
- Commit often with clear messages.
- Pull changes regularly to minimize conflicts.