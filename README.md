# Template git messages

Structure of a good commit.

## Description

Some tips so that the content of our commits is precise, easy to write, easy to read and easy to interpret.

**Tips for git messages:**

1. Separate the title from the description using a blank line
2. The title must not contain more than 50 characters
3. The first word of the title is capitalized
4. Don't end the title with a period
5. Use the imperative mood in the title line
6. the description must not contain more than 72 characters per line
7. Use description to explain what and why versus how

**Type of title:**

- **feat**     (new feature)
- **fix**      (bug fix)
- **refactor** (refactoring code)
- **style**    (formatting, missing semi colons, etc; no code change)
- **doc**      (changes to documentation)
- **test**     (adding or refactoring tests; no production code change)
- **version**  (version bump/new release; no production code change)
- **jsrXXX**   (Patches related to the implementation of jsrXXX, where XXX the JSR number)
- **jdkX**     (Patches related to supporting jdkX as the host VM, where X the JDK version)
- **dbg**      (Changes in debugging code/frameworks; no production code change)
- **license**  (Edits regarding licensing; no production code change)
- **hack**     (Temporary fix to make things move forward; please avoid it)
- **wip**      (Work In Progress; for intermediate commits to keep patches reasonably sized)
- **defaults** (changes default options)

**Commit structure:**

```markdown
Title: ########50 characters###################

Body: Explain *what* and *why* (not *how*). ########72 characters####

- The bullets are fine too
- Typically a dash or asterisk is used for the bullets
- Followed by a single space, with blank lines in between
- Using a hanging indentation

Github issue #123 (Optional)

Note:
Special instructions, testing steps, rake, etc

At the end: Include Co-authored-by for all contributors.
Co-authored-by: name <user@users.noreply.github.com>
```

**Example:**

```markdown
feat: Add a new feature

This is a longer description of the commit. It should explain what the
commit does and why it is needed. It should be written in a way that is
understandable to a wide audience.

- The first line of the body should be 72 characters or less
- The second line should be blank
- The third line should be 72 characters or less

Github issue #123

Note:
Special instructions, testing steps, rake, etc

Co-authored-by: name <user@users.noreply.github.com>
```

## Starting 🚀

Instructions to obtain a copy of the project and implement it on a local machine for development and testing.

### Pre-requisites 📋

Dependencies to run the project:

- Operating system Linux, Windows, MacOs all Versions.
- Git all Version.
- Know the markdown language.
- Don't be afraid of the terminal.

### Installation 🔧

Steps to install and run the project locally:

Clone the project:

```bash
git clone git@github.com:brayandiazc/gitmessage-template.git
```

Change the directory to the project:

```bash
cd gitmessage-template
```

Copy the template files to the project:

```bash
cp .gitmessage-template/* .
```

Change to root directory:

```bash
cd
```

Config the git message template:

```bash
git config --global commit.template ~/.gitmessage
```

**Instructions for copy file:**

## Built with 🛠️

Tools used to create the project

- [Markdown](https://en.wikipedia.org/wiki/Markdown) - Language used
- [Git](https://git-scm.com/) - Version control system

## Versioning 📌

Version control system [Git](https://git-scm.com).

## Authors ✒️

People who have contributed to the project:

- **Brayan Diaz C** - _Initial Work_ - [brayandiazc](https://github.com/brayandiazc)

## License 📄

This project is under the License MIT License. - see the file [LICENSE.md] (LICENSE.md) for details

---

⌨️ with ❤️ by [Brayan Diaz C](https://brayandiazc.com) 😊
