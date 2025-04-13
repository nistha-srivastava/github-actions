# GitHub Actions Playground 🚀

This is a public repository created while learning **GitHub Actions**. It contains multiple workflows to explore and understand how GitHub Actions work in real-world automation and CI/CD setups.

## 🧠 What This Repository Covers

As part of the learning journey, the following workflows have been created:

### 1. Hello World Workflow 🌍
A basic workflow that:
- Prints `Hello World` to the runner logs.
- Helps understand the basic structure of a GitHub Actions workflow.

### 2. React App Automated Testing 🧪
A more involved workflow that:
- Uses a sample React app.
- Clones the repository on a GitHub-hosted runner.
- Installs dependencies via `npm ci`.
- Runs the test suite using `npm test`.
- Leverages predefined GitHub Actions like `actions/checkout` and `actions/setup-node`.

### 3. GitHub Context Exploration 🧩
A workflow created to:
- Inspect the **GitHub context object** (`github`).
- Learn how to extract and use specific fields like event name, actor, commit SHA, etc.
- Understand how workflows can dynamically react based on the context.

### 4. Event Triggers and Filters 🎯
Using the same React app, this workflow focuses on:
- Responding to **multiple GitHub event types** (like `push`, `pull_request`).
- Applying **filters** (e.g., path filters, event types).
- Understanding event activity types and refining when workflows run.




## 📚 Learning Source

This repository is part of a hands-on course/tutorial on **GitHub Actions**. It demonstrates concepts through actual workflows and is meant to serve as both a reference and a sandbox for experimenting with CI/CD automation.

> 📘 Source of learning: [GitHub Actions - The Complete Guide](https://www.udemy.com/course/github-actions-the-complete-guide/) on Udemy
