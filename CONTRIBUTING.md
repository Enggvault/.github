# Contributing to EnggVault

First off, thank you for considering contributing to EnggVault! It's people like you that make open source such a great community.

We welcome contributions from everyone—whether it's fixing a bug, adding a new feature, improving documentation, or suggesting an idea.

## 📋 Table of Contents

- [Development Workflow](#-development-workflow)
- [Branch Naming](#-branch-naming)
- [Commit Message Conventions](#-commit-message-conventions)
- [Pull Request Process](#-pull-request-process)
- [Coding Standards](#-coding-standards)
- [Folder Structure](#-folder-structure)
- [Issue Reporting](#-issue-reporting)
- [Documentation Standards](#-documentation-standards)
- [Code Review Expectations](#-code-review-expectations)
- [Community Etiquette](#-community-etiquette)

---

## 🔄 Development Workflow

1. **Fork the repository** you want to contribute to.
2. **Clone your fork** locally: `git clone https://github.com/YOUR-USERNAME/REPO-NAME.git`
3. **Create a new branch** for your feature or bugfix (see [Branch Naming](#-branch-naming)).
4. **Make your changes** and commit them (see [Commit Message Conventions](#-commit-message-conventions)).
5. **Push your branch** to your fork: `git push origin your-branch-name`
6. **Open a Pull Request** against the `main` branch of the original repository.

## 🌿 Branch Naming

We use the following conventions for branch names:

- `feat/short-description`: For new features.
- `fix/short-description`: For bug fixes.
- `docs/short-description`: For documentation changes.
- `chore/short-description`: For maintenance, refactoring, or tooling updates.
- `test/short-description`: For adding or updating tests.

*Example:* `feat/add-user-authentication` or `fix/header-alignment-issue`

## 📝 Commit Message Conventions

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification. This helps us generate changelogs automatically and maintain a readable commit history.

Format: `type(scope): subject`

**Types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools and libraries

*Example:* `feat(auth): implement JWT token verification`

## 🚀 Pull Request Process

1. **Use the Template**: When opening a PR, please fill out the provided `PULL_REQUEST_TEMPLATE`.
2. **Link Issues**: If your PR fixes an open issue, link it using closing keywords (e.g., `Closes #123`).
3. **Keep it Small**: Try to keep PRs focused on a single change. Large PRs are harder to review.
4. **Pass Checks**: Ensure all CI/CD checks (linting, tests, builds) pass before requesting a review.
5. **Review**: A core maintainer will review your code. Address any feedback promptly.

## 💻 Coding Standards

- Write clean, readable, and self-documenting code.
- Follow the specific style guide configured for the project (e.g., Prettier, ESLint).
- Ensure your code doesn't introduce any new linting errors or warnings.
- Write unit tests for new features or bug fixes whenever possible.

## 📁 Folder Structure

While folder structures vary by project, we generally adhere to standard conventions for the specific technology stack being used (e.g., standard Next.js `app/` structure, standard Go project layout). 

Please review the specific repository's `README.md` or existing code to understand its structure before contributing.

## 🐛 Issue Reporting

If you find a bug or have a feature request, please open an issue!

- Use the provided **Issue Templates**.
- Be as descriptive as possible.
- Include steps to reproduce for bugs.
- Provide environment details (OS, Node version, browser, etc.) if applicable.

## 📖 Documentation Standards

Good documentation is just as important as good code.

- Update the `README.md` if you introduce a breaking change or a major new feature.
- Use clear, concise language.
- Add code comments to explain *why* something is done, not just *what* it does, especially for complex logic.
- Ensure any added Markdown is formatted correctly.

## 👀 Code Review Expectations

- **Be Respectful**: Reviews are about improving the code, not criticizing the author.
- **Be Clear**: Explain why a change is requested.
- **Respond to Feedback**: If a maintainer leaves a comment, please respond or make the requested change.
- **Ask Questions**: If you don't understand a piece of feedback, ask for clarification.

## 🤝 Community Etiquette

Please read and abide by our [Code of Conduct](https://github.com/Enggvault/.github/blob/main/CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inspiring community for everyone.
