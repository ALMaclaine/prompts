# Commit Message Generation Prompt

Use this prompt to generate clear and consistent commit messages following the Conventional Commits standard.

## Purpose
Ensure commit messages are informative and standardized to improve project history readability.

## Steps

1. **Review Changes**:
   - Use `git status` and `git diff` to see what has changed.

2. **Determine the Type of Change**:
   - **feat**: Introducing a new feature.
   - **fix**: Bug fixes.
   - **docs**: Documentation changes.
   - **style**: Code style changes (formatting, missing semicolons).
   - **refactor**: Code changes without fixing bugs or adding features.
   - **perf**: Performance improvements.
   - **test**: Adding or updating tests.
   - **chore**: Maintenance tasks.

3. **Specify the Scope** (optional):
   - Indicate the section of the codebase (e.g., `auth`, `api`, `utils`).

4. **Write a Short Description**:
   - Summarize the changes in 50 characters or less.

5. **Add an Extended Description** (optional):
   - Provide additional context or reasoning.
   - Mention any issues closed (e.g., `Closes #123`).
   - Note if there are breaking changes.

6. **Compose the Commit Message**:
   ```
   <type>(<scope>): <short description>

   <extended description>

   [Optional footer(s)]
   ```

7. **Commit Your Changes**:
   - Stage your changes: `git add .`
   - Commit: `git commit -m "Your commit message"`

## Example
```
feat(auth): add OAuth2 login support

Implemented OAuth2 authentication with Google and Facebook providers.
Updated the user model and login UI accordingly.

Closes #45
```