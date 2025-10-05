# TDS September Assignment

This repository contains a GitHub Action created for the TDS September assignment.

## GitHub Action

The repository includes a GitHub Action workflow located at `.github/workflows/main.yml` that:

- Triggers on push to the main branch
- Can be manually triggered via workflow_dispatch
- Contains a verification step with the required email address: `23f3004197@ds.study.iitm.ac.in`
- Performs basic system checks and creates verification artifacts

## Workflow Features

1. **Verification Step**: Contains the required email address in the step name
2. **System Information**: Displays runner and environment details
3. **Artifact Creation**: Creates and uploads a verification file
4. **Manual Trigger**: Can be run manually from the GitHub Actions tab

## Usage

The action will automatically run when code is pushed to the main branch, or it can be triggered manually from the GitHub Actions tab in the repository.

## Assignment Requirements

This GitHub Action fulfills the requirement of having a step named with the email address `23f3004197@ds.study.iitm.ac.in` for the TDS September assignment verification.