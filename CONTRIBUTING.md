# Contributing to Universal POS Core

First off, thanks for taking the time to contribute! 🎉

The following is a set of guidelines for contributing to Universal POS Core. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
- [Styleguides](#styleguides)
  - [Git Commit Messages](#git-commit-messages)
  - [TypeScript Styleguide](#typescript-styleguide)

## Code of Conduct

This project and everyone participating in it is governed by the [Universal POS Core Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [INSERT EMAIL ADDRESS].

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Universal POS Core. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

> **If you find a security vulnerability, please DO NOT report it through a public GitHub issue.** Instead, please send an email to [INSERT SECURITY EMAIL].

#### Before Submitting A Bug Report

- Check the [Issues](https://github.com/senseikatana/pos-system/issues) to see if the problem has already been reported. If it has and the issue is still open, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A Bug Report?

Explain the problem and include additional details to help maintainers reproduce the problem:

1.  **Use a clear and descriptive title** for the issue to identify the problem.
2.  **Describe the exact steps which reproduce the problem** in as many details as possible.
3.  **Describe the behavior you observed** after following the steps and point out what exactly is the problem with that behavior.
4.  **Explain which behavior you expected to see instead and why.**
5.  **Include screenshots and animated GIFs** if possible.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Universal POS Core.

#### How Do I Submit An Enhancement Suggestion?

1.  **Use a clear and descriptive title** for the issue to identify the suggestion.
2.  **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
3.  **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
4.  **Include screenshots and animated GIFs** if possible.

### Your First Code Contribution

Unsure where to start contributing? You can start by looking through these `beginner` and `help-wanted` issues:

- [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
- [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

[beginner]: https://github.com/senseikatana/pos-system/labels/beginner
[help-wanted]: https://github.com/senseikatana/pos-system/labels/help%20wanted

### Pull Requests

- Fill in [the required template](PULL_REQUEST_TEMPLATE.md).
- Do not include issue numbers in the PR title
- Include screenshots and animated GIFs in your pull request whenever possible.
- Follow the [TypeScript Styleguide](#typescript-styleguide).
- Include thoughtfully-worded, well-structured tests.
- Document new code based on the [Documentation Styleguide](#documentation-styleguide).
- End all files with a newline.

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

### TypeScript Styleguide

All JavaScript and TypeScript code is formatted with [Prettier](https://prettier.io/), and we enforce the rules defined in the `.eslintrc` and `tsconfig.json` files.

- Use `const` for all variable declarations.
- Use arrow functions `() => {}` instead of `function` declarations.
- Always specify explicit return types.
- Prefer named exports over default exports.
