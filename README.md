# GitHub Actions Demo

This repository contains a GitHub Actions workflow to demonstrate basic CI/CD features.

## Workflow

The workflow file is located at `.github/workflows/github-actions-demo.yml` and runs automatically on every push to the repository.

### What it does

- Triggered on every `push` event
- Runs on `ubuntu-latest`
- Displays information about the trigger event, runner, branch, and repository
- Checks out the repository code using `actions/checkout@v5`
- Lists all files in the repository
- Reports the job status

## Getting Started

1. Push this repository to GitHub
2. Go to the **Actions** tab in your repository
3. View the "GitHub Actions Demo" workflow runs
4. Click on a run to see the job logs and step details

## Learn More

- [GitHub Actions Quickstart](https://docs.github.com/en/actions/get-started/quickstart)
- [Understanding GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
- [Workflow Syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
