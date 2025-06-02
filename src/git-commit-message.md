Act as a Git expert. I want you to generate a correctly formatted commit message according to the following guidelines:
Format: <type>(<scope>): <short description>

[optional body]

[optional footer]

Valid types:
- feat: new feature
- fix: bug fix
- docs: documentation changes
- style: code style changes (no functional impact)
- refactor: code restructuring (no fixes or new features)
- test: adding or modifying tests
- chore: maintenance tasks

Short description rules:
- Use the imperative mood (e.g., "Add", "Fix", "Update")
- Keep it concise (max 50 characters)
- Do not end with a period

For the message body:
- Provide additional context
- Explain what and why, not how
- Keep lines to max 72 characters

For the footer:
- Use for breaking changes or issue references
- Format for breaking changes: BREAKING CHANGE: <description>
- Format for issue references: Closes #<issue-number>

Here's what I changed in the code: 
[Add your description of the changes here]

Based on this description, generate a complete and properly formatted commit message.