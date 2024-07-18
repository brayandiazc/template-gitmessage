# Git Message Template Repository

This repository contains a Git message template designed to help standardize and streamline commit messages across your projects. Consistent and clear commit messages are essential for maintaining a readable and maintainable project history.

## Description

Some tips so that the content of our commits is precise, easy to write, easy to read, and easy to interpret.

## Tips for Git Messages

1. Separate the title from the description using a blank line.
2. The title must not contain more than 50 characters.
3. Capitalize the first word of the title.
4. Do not end the title with a period.
5. Use the imperative mood in the title line.
6. The description must not contain more than 72 characters per line.
7. Use the description to explain what and why versus how.

### Recommended Title Types

- **feat**: New feature
- **fix**: Bug fix
- **refactor**: Refactoring code
- **style**: Formatting, missing semi-colons, etc.; no code change
- **docs**: Changes to documentation
- **test**: Adding or refactoring tests; no production code change
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation
- **perf**: Code change that improves performance
- **ci**: Changes to our CI configuration files and scripts (e.g., GitHub Actions, CircleCI)
- **build**: Changes that affect the build system or external dependencies (e.g., gulp, broccoli, npm)
- **revert**: Reverts a previous commit
- **wip**: Work In Progress; for intermediate commits to keep patches reasonably sized
- **hack**: Temporary fix to make things move forward; please avoid it

## Commit Structure

### Title (Subject Line)

- **Purpose**: Summarizes the changes concisely.
- **Format**: `<type>: <subject>`
- **Example**:

```markdown
feat: add user authentication
```

### Body (Detailed Description)

- **Purpose**: Provides a more detailed explanation of the changes made and why they were made.
- **Format**: Use the imperative mood (e.g., "Add", "Fix", "Update"). Wrap text at 72 characters. Separate paragraphs with a blank line.
- **Example**:

```markdown
Fix issue with user login process by updating
the authentication method. The previous method
was not compatible with the new security requirements.

This fix ensures that users can log in without errors
and improves the overall security of the application.
```

### Footer (Optional)

- **Purpose**: Includes any additional information, such as related issue numbers or references.
- **Format**: Use keywords like `Closes`, `Fixes`, `Refs`, followed by the issue number.
- **Example**:

```markdown
Closes #123
```

### Note

- **Purpose**: Special instructions, testing steps, rake tasks, etc.
- **Example**:

```markdown
Note:
Special instructions, testing steps, rake, etc.
```

### Co-authored-by

- **Purpose**: Include for all contributors at the end of the commit message.
- **Format**: `Co-authored-by: name <user@users.noreply.github.com>`
- **Example**:

```markdown
Co-authored-by: John Doe <john.doe@example.com>
```

## Example Commit Message

```markdown
feat: add user authentication

Add a new feature for user authentication using JWT. This feature allows
users to securely log in and receive a token for subsequent requests.

- Implemented JWT-based authentication
- Added middleware to protect routes
- Updated user model to include authentication methods

Closes #45

Note:

- Remember to update environment variables with JWT secret key.
- Ensure database migrations are applied before testing.

Co-authored-by: Jane Doe <jane.doe@example.com>
```

## How to Use the Template

1. Clone the Repository: Clone this repository to your local machine.

```bash
git clone git@github.com:brayandiazc/template-gitmessage.git
```

2. Navigate to the Root Directory: Change to the directory where you cloned the repository.

```bash
cd template-gitmessage
```

3. Copy the Template File: Copy the .gitmessage file to your root directory.

```bash
cp .gitmessage ~
```

4. Configure Git: Set the template as your default commit message template by running the following command:

```bash
git config --global commit.template ~/.gitmessage
```

## Author

- [Brayan Diaz C](https://github.com/brayandiazc)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Additional Tips

Here are some extra tips to make the most out of your README:

- Keep each section as concise as possible. Avoid unnecessary information as it can be overwhelming for the reader.
- Ensure your installation and deployment instructions are detailed and precise. If there are additional steps the reader needs to take (such as installing extra dependencies), make sure to include them.
- Visuals (images, GIFs) are very helpful to quickly convey what your project does and how to use it. If possible, include screenshots of your application in action or GIFs demonstrating its use.

---

⌨️ with ❤️ by [Brayan Diaz C](https://github.com/brayandiazc) 😊
