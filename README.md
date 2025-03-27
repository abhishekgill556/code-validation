# CI/CD with GitHub Actions

This is a practice project for implementing a basic CI/CD pipeline using GitHub Actions and Super-Linter.

## What it does

- Lints code automatically on every push or pull request to the `main` branch.
- Follows GitHub workflow best practices using branches and code review.

## How it works

1. All development is done in the `dev` branch.
2. Changes are reviewed and approved through pull requests.
3. Once merged into `main`, the Super-Linter GitHub Action checks the code for issues.

## Author

Created by Abhishek Gill for CI/CD assignment practice.
