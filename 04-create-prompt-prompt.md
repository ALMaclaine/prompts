# Create Prompt Prompt

Use this prompt when you need to create a new prompt to support the development process.

## Purpose
Provide a consistent structure for creating new prompts that enhance the workflow.

## Steps

1. **Define the Purpose**:
   - Clearly articulate why the new prompt is needed.
   - Determine the specific problem it addresses.

2. **Name the Prompt**:
   - Choose a descriptive and concise name.
   - Use lowercase with underscores (e.g., `deployment_process_prompt.md`).

3. **Create the Prompt File**:
   - Place it in the `prompt/` directory.

4. **Structure the Prompt**:
   - **Title**: Begin with a clear, descriptive title.
   - **Purpose**: Explain when and why to use the prompt.
   - **Steps**: List step-by-step instructions.
   - **Examples**: Include examples if applicable.

5. **Review and Refine**:
   - Check for clarity and completeness.
   - Ensure it aligns with project standards.

6. **Update the Prompt Index**:
   - Add the new prompt to `prompt/prompt_index.md` with a brief description.

7. **Commit the New Prompt**:
   - Use the [Commit Message Generation Prompt](#3-commit-message-generation-prompt) for your commit message.

## Example Structure
```markdown
# [Prompt Title]

## Purpose
[Explain the purpose and when to use this prompt.]

## Steps

1. [First Step]
2. [Second Step]
3. [And so on...]

## Examples
[Include any relevant examples.]
```