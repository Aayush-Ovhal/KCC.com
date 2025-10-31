# KCC.com
# 👋 Welcome Bot using GitHub Actions

This repository contains a simple **GitHub Action** workflow that automatically sends a greeting message when someone creates their **first issue** or **first pull request** in this repository.

## ⚙️ How It Works

The workflow uses the [`actions/first-interaction`](https://github.com/actions/first-interaction) GitHub Action to detect when a contributor interacts for the first time.

Whenever a new contributor:
- Creates their **first issue**, they’ll receive a predefined greeting message.  
- Opens their **first pull request**, they’ll receive a welcoming message encouraging contribution.

## 🧩 Workflow File

The workflow file is located at: .github\workflows

