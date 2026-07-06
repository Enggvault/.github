# Contributing to EnggVault

Thank you for your interest in contributing to EnggVault. We value your time and effort. We welcome contributions from everyone, whether it involves fixing bugs, adding features, improving documentation, or suggesting new ideas.

## Table of Contents

- [Development Workflow](#development-workflow)
- [Branch Naming](#branch-naming)
- [Commit Message Conventions](#commit-message-conventions)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Folder Structure](#folder-structure)
- [Issue Reporting](#issue-reporting)
- [Documentation Standards](#documentation-standards)
- [Code Review Expectations](#code-review-expectations)
- [Community Etiquette](#community-etiquette)

---

## Development Workflow

1. **Fork the repository** you want to contribute to.
2. **Clone your fork** locally: `git clone https://github.com/YOUR-USERNAME/REPO-NAME.git`
3. **Create a new branch** for your feature or bugfix (see [Branch Naming](#branch-naming)).
4. **Make your changes** and commit them (see [Commit Message Conventions](#commit-message-conventions)).
5. **Push your branch** to your fork: `git push origin your-branch-name`
6. **Open a pull request** against the `main` branch of the original repository.

## Branch Naming

We use the following conventions for branch names:

- `feat/short-description`: For new features.
- `fix/short-description`: For bug fixes.
- `docs/short-description`: For documentation changes.
- `chore/short-description`: For maintenance, refactoring, or tooling updates.
- `test/short-description`: For adding or updating tests.

*Example:* `feat/add-user-authentication` or `fix/header-alignment-issue`

## Commit Message Conventions

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification. This practice helps us automatically generate changelogs and maintain a readable commit history.

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

## Pull Request Process

1. **Use the Template**: When opening a pull request, please fill out the provided `PULL_REQUEST_TEMPLATE`.
2. **Link Issues**: If your PR resolves an open issue, link it using closing keywords (e.g., `Closes #123`).
3. **Keep it Focused**: Attempt to keep pull requests focused on a single change. Large PRs are inherently more difficult to review.
4. **Pass Checks**: Ensure all CI/CD checks (linting, tests, builds) pass before requesting a review.
5. **Review**: A core maintainer will review your code. Please address any feedback promptly.

## Coding Standards

- Write clean, readable, and self-documenting code.
- Adhere to the specific style guide configured for the project (e.g., Prettier, ESLint).
- Ensure your changes do not introduce new linting errors or warnings.
- Write unit tests for new features or bug fixes whenever possible.

## Folder Structure

Folder structures vary by project. We generally adhere to standard conventions for the specific technology stack being used. 

Please review the repository's `README.md` or existing code architecture to familiarize yourself with its structure before contributing.

## Issue Reporting

If you find a bug or have a feature request, please open an issue.

- Use the provided **Issue Templates**.
- Be as descriptive as possible.
- Include step-by-step instructions to reproduce bugs.
- Provide environment details (OS, Node version, browser, etc.) if applicable.

## Documentation Standards

Accurate documentation is critical to project maintainability.

- Update the `README.md` if you introduce a breaking change or a major new feature.
- Use clear, professional language.
- Add code comments to explain the reasoning behind complex logic.
- Ensure any added Markdown is formatted correctly.

## Code Review Expectations

- **Maintain Professionalism**: Reviews are intended to improve the codebase, not to critique the author.
- **Communicate Clearly**: Explain the reasoning behind requested changes.
- **Respond Constructively**: If a maintainer leaves a comment, please respond or implement the requested change.
- **Ask Questions**: If you are uncertain about a piece of feedback, please ask for clarification.

## Community Etiquette

Please read and abide by our [Code of Conduct](https://github.com/Enggvault/.github/blob/main/CODE_OF_CONDUCT.md). We are committed to providing a professional and welcoming community for all participants.
