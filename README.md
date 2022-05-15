# Template git messages

Structure of a good commit.

## Description

Some tips so that the content of our commits is precise, easy to write, easy to read and easy to interpret.

**Tips for git messages:**

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

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
- **WIP**      (Work In Progress; for intermediate commits to keep patches reasonably sized)
- **defaults** (changes default options)

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

1. Clone the project:

```bash
git clone git@github.com:brayandiazc/gitmessage-template.git
```

2. Change the directory to the project:

```bash
cd gitmessage-template
```

3. Copy the template files to the project:

```bash
cp -r .gitmessage-template/* .
```

4. Change to root directory:

```bash
cd
```

5. Confgig the git message template:

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

- **Brayan DIaz C** - _Initial Work_ - [brayandiazc](https://github.com/brayandiazc)

## License 📄

This project is under the License MIT License. - see the file [LICENSE.md] (LICENSE.md) for details

---

⌨️ with ❤️ by [Brayan Diaz C](https://github.com/brayandiazc) 😊
