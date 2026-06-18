# Contributing to PtheusLab

Thank you for your interest in contributing. This document covers everything you need to get started.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Workflow](#workflow)
- [Commit Convention](#commit-convention)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Issues](#reporting-issues)

---

## Code of Conduct

Be respectful, constructive, and professional. We do not tolerate harassment or discrimination of any kind.

---

## Getting Started

1. **Fork** this repository
2. **Clone** your fork locally

   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Create a branch** for your changes

   ```bash
   git checkout -b feat/your-feature-name
   ```

---

## Workflow

```
fork → branch → commit → push → pull request → review → merge
```

- Always branch off `main`
- Keep changes focused — one feature or fix per PR
- Write or update tests when applicable
- Ensure all checks pass before requesting review

---

## Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/).

```
<type>: <short description>
```

| Type | When to use |
|------|-------------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation only |
| `refactor` | Code change, no new feature or fix |
| `test` | Adding or updating tests |
| `chore` | Build process, tooling, or config |

**Examples:**

```
feat: add rate limiting to API middleware
fix: resolve token expiry edge case
docs: update setup instructions
```

---

## Pull Request Guidelines

- Use a clear, descriptive title following the commit convention
- Fill out the PR template completely
- Reference related issues with `Closes #issue-number`
- Keep PRs small and reviewable — large PRs take longer to merge
- Be responsive to review feedback

---

## Reporting Issues

Before opening an issue:

1. Search existing issues to avoid duplicates
2. Reproduce the problem on the latest version

When reporting, include:

- Steps to reproduce
- Expected vs. actual behavior
- Environment details (OS, Node.js version, etc.)
- Relevant logs or screenshots

---

## Questions?

Open a [Discussion](https://github.com/ptheuslab/discussions) or reach out via the community channels listed in the README.

---

<div align="center">

**PtheusLab** · Open by Design. Trusted by Developers.

</div>
