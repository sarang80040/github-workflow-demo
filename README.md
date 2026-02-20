# GitHub Workflow Demo

## About This Project

This project demonstrates a simple **GitHub Actions workflow** that runs an animated typing effect in the CI/CD pipeline logs.

## What is a GitHub Workflow?

A GitHub Workflow is an automated process defined in a YAML file inside `.github/workflows/`. Workflows are triggered by events such as pushes, pull requests, or on a schedule. They consist of one or more **jobs**, each containing a series of **steps** that run commands or actions.

## How This Workflow Works

- **Trigger:** This workflow runs automatically every time code is pushed to the `main` branch.
- **Job:** It executes a single job called `greet` on an Ubuntu runner.
- **Animated Typing:** The job displays an animated typing effect in the GitHub Actions logs, printing the message *"Welcome to GitHub Workflows!"* one character at a time.
- **Output:** After the animation, it prints a success confirmation message.

## Viewing the Workflow

1. Go to the **Actions** tab in this repository.
2. Click on the latest workflow run.
3. Open the `greet` job logs to see the animated typing output.
