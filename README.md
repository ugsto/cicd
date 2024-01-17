# GitHub Actions Example Repository

[![Tests](https://github.com/ugsto/cicd/actions/workflows/tests.yml/badge.svg)](https://github.com/ugsto/cicd/actions/workflows/tests.yml)

## Overview

Welcome to the example repository demonstrating the use of GitHub Actions with a simple NodeJS module. This repository serves as a practical showcase, providing an example of how to integrate and utilize GitHub Actions in a NodeJS application for automated workflows.

## Purpose

The purpose of this repository is to illustrate the setup, configuration, and advantages of using GitHub Actions in a NodeJS environment. Whether you're new to CI/CD concepts or looking to see GitHub Actions in action, this repository provides a really simple example to help you understand and implement these practices in your own projects.

## Repository Structure

- `.github/workflows/`: Contains the GitHub Actions workflow files. Here you can find the YAML configuration that defines the NodeJS CI workflow.
- `tests/`: Contains test scripts for the NodeJS application.
- `README.md`: Provides an overview and guide to this repository.

## Workflow Details

The included GitHub Actions workflow is designed to perform the following tasks:

1. **Install Dependencies:** Upon each push or pull request to the master branch, the workflow installs necessary NodeJS dependencies.
2. **Run Tests:** Executes the test scripts located in the `tests/` directory.

## Getting Started

Setting up GitHub Actions:

1. Using GitHub's UI:

- Navigate to the 'Actions' tab in your GitHub repository.
- Click 'New workflow'.
- Select a workflow template or start from scratch.
- Edit the workflow file in the web editor and commit it to a new branch or directly to the main branch.

2. Manually Creating Workflow File:

- Create a new file in the .github/workflows/ directory in your repository.
- Name it with a .yml extension (e.g., nodejs.yml).
- Define your workflow in this file using YAML syntax.
- Commit and push the file to your repository.
- Make Changes and Observe: Experiment by making changes to the code or the workflow file. Observe how GitHub Actions processes these changes with each push or pull request.

## License

This repository is open-sourced under the [MIT license](LICENSE).
