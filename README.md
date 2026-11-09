# Datacom Cloud & DevOps — GitHub Actions Workflow

A hands-on DevOps learning project developed as part of the **Datacom Introduction to Cloud Job Simulation**, hosted on Forage.

This repository demonstrates the fundamentals of Git version control, GitHub Actions automation, YAML configuration, and repository variables.

## Project Overview

The goal of this project is to create and execute a basic automated workflow using GitHub Actions.

The workflow is triggered whenever code is pushed to the repository and can also be executed manually.

## Technologies Used

- Git & GitHub
- GitHub Actions
- YAML
- Bash
- Visual Studio Code
- Ubuntu GitHub-hosted runner

## Project Structure

```text
datacom-cloud-devops/
├── .github/
│   └── workflows/
│       └── first-workflow.yml
└── README.md
```

## How It Works

The workflow performs the following operations:

1. Starts automatically when a push event occurs.
2. Runs a job on an Ubuntu-hosted runner.
3. Retrieves a repository variable named `GREETING`.
4. Prints the greeting message in the workflow logs.
5. Executes a final confirmation command.

The workflow also supports manual execution through `workflow_dispatch`.

## Repository Variables

The project uses a GitHub Actions repository variable:

| Variable | Example Value |
|---|---|
| `GREETING` | `Hello from Datacom!` |

This demonstrates how GitHub Actions can access non-sensitive configuration values without hardcoding them directly into workflow commands.

## Execution Results

The initial workflow execution completed successfully.

**Workflow:** My First Datacom Workflow  
**Trigger:** Push  
**Status:** Success  
**Total Duration:** 6 seconds

Expected output:

```text
Hello from Datacom!
Workflow completed successfully!
```

## Key Learnings

Through this project, I practiced:

- Creating and configuring Git repositories.
- Working with Git commands through the terminal.
- Managing commits and pushing changes to GitHub.
- Writing YAML workflow configurations.
- Using GitHub Actions repository variables.
- Understanding the fundamentals of workflow automation.

## Future Improvements

- Add automated tests to a sample application.
- Implement a basic CI pipeline.
- Explore deployment automation.
- Learn more about cloud infrastructure and Infrastructure as Code.

## Acknowledgment

This project was completed as part of the Datacom Introduction to Cloud Job Simulation on Forage.

It is an independent educational project and is not an official Datacom product.

## Author

**Yasmim Stephanie**

[GitHub](https://github.com/YasmimStephanie) | [LinkedIn](https://www.linkedin.com/in/yasmim-stephanie/)
