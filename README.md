# Country Poverty Analysis

## 🚀 Quick Start Follow these steps to set up the project from scratch. 
### 1️⃣ Prerequisites Make sure you have: 
- **Python 3.12** or newer 
- **Poetry** 
- - Installed and accessible from your terminal Check both:
```bash
python --version
poetry --version
```
### 2️⃣ Clone the Repository

Once Poetry and Python are ready, clone the repository and navigate into it:

```bash
git clone https://github.com/<your-org-or-user>/countrypovertyanalysis.git
cd countrypovertyanalysis

# Configure Poetry to keep .venv inside the project
poetry config virtualenvs.in-project true

# Create the virtual environment and install dependencies
poetry install
```

# 🤝 Contributing Guide

Thank you for your interest in contributing to **Country Poverty Analysis**!  
This guide explains how to collaborate using Git branches for new features, bug fixes, and other improvements.

---

## 🧭 Branching Strategy

We use a **simplified Git Flow** model with the following branch types:

| Branch Type | Prefix | Purpose |
|--------------|---------|----------|
| **Main** | `main` | The production-ready branch. Always stable. |
| **Development** | `develop` | The integration branch where new work is merged. |
| **Feature** | `feature/<name>` | New features or enhancements. |
| **Fix** | `fix/<name>` | Non-critical bug fixes or small patches. |
| **Hotfix** | `hotfix/<name>` | Urgent fixes applied directly to `main`. |
| **Release** | `release/<version>` | Prepares a stable version before merging to `main`. |

---

## 🧠 Commit Message Convention

Follow the **Conventional Commits** style for clarity:

| Type       | Description                                 | Example                                   |
| ----------- | ------------------------------------------- | ----------------------------------------- |
| `feat`     | New feature                                 | `feat(ui): add country selector dropdown` |
| `fix`      | Bug fix                                     | `fix(data): correct missing GDP column`   |
| `docs`     | Documentation changes                       | `docs: update installation guide`         |
| `style`    | Code style or formatting (no logic changes) | `style: apply black formatting`           |
| `refactor` | Code refactoring                            | `refactor(core): simplify data parsing`   |
| `test`     | Add or fix tests                            | `test: add unit tests for data parser`    |
| `chore`    | Maintenance tasks                           | `chore: update dependencies`              |


LICENSE - [Creative Commons Atribución–NoComercial 4.0 Internacional (CC BY-NC 4.0)](https://github.com/Instituto-Juan-de-Mariana/country-poverty-analysis?tab=License-1-ov-file)
