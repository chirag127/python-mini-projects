# Contributing Guidelines

## 🚀 Welcome to the Apex Collective!

Thank you for considering contributing to this repository. As an **Apex Technical Authority** project, we uphold the highest standards of code quality, architectural integrity, and collaborative efficiency. Your contributions help us maintain our **Zero-Defect, High-Velocity, Future-Proof** philosophy.

## 🎯 Project Vision

This repository is a collection of **Python Utility Scripts** and **Micro-Projects** designed to enhance practical Python programming skills and demonstrate best practices. It serves as a curated platform for learning, experimentation, and the development of robust, reusable Python solutions.

## 💡 How to Contribute

We welcome contributions in various forms, from bug fixes and feature enhancements to documentation improvements and new utility scripts. Please adhere to the following guidelines:

### 1. Code of Conduct

All contributors must adhere to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/0/CODE_OF_CONDUCT.html). We strive for a respectful, inclusive, and professional environment.

### 2. Getting Started

*   **Fork the Repository:** Create your own fork of the repository.
*   **Clone Your Fork:** `git clone https://github.com/chirag127/Python-Utility-Scripts-And-Micro-Projects-Collection.git`
*   **Set Up Development Environment:**
    *   Ensure you have Python 3.10+ installed.
    *   Use `uv` for dependency management: `uv venv .venv` and `source .venv/bin/activate`.
    *   Install project dependencies: `uv pip install -e .[dev]` (if a `pyproject.toml` with dev dependencies is present).
    *   If no `pyproject.toml`, install directly: `uv pip install -r requirements.txt` (and `requirements-dev.txt`).
*   **Create a New Branch:** `git checkout -b feature/your-feature-name` or `bugfix/your-bug-fix`.

### 3. Development Workflow

*   **Adhere to Apex Standards:** All code must follow the **Apex Technical Stacks (Late 2025 Standards)**, specifically for Python: **uv**, **Ruff**, **Pytest**, and **Modular Monolith** architecture principles.
*   **Linting & Formatting:** Code must pass **Ruff** checks. Run `ruff check .` and `ruff format .` before committing.
*   **Testing:** All new features or bug fixes must include comprehensive **Pytest** tests. Run `pytest` to ensure all tests pass.
*   **Documentation:** Update relevant documentation (e.g., docstrings, README sections if applicable) for any changes.
*   **Commit Messages:** Follow conventional commit message formatting (e.g., `feat: add new utility script for file processing` or `fix: resolve bug in data validation script`).
*   **Pull Requests (PRs):**
    *   Open PRs against the `main` branch.
    *   Provide a clear and concise description of your changes.
    *   Ensure all CI checks pass.
    *   Reference any relevant issues.

### 4. Contribution Types

*   **New Utility Scripts:** If you have a useful Python utility script, please consider contributing it. Ensure it follows best practices, includes docstrings, and has tests if applicable.
*   **Micro-Projects:** Substantial new micro-projects should be well-defined, modular, and demonstrate clear learning objectives or practical applications.
*   **Bug Fixes:** If you find a bug, please open an issue first (if one doesn't exist) and then submit a PR with the fix.
*   **Documentation:** Improvements to README files, docstrings, or CONTRIBUTING guidelines are always welcome.
*   **Refactoring:** Suggestions for improving code structure, readability, or performance are valuable, provided they align with Apex architectural principles.

### 5. Code Structure & Architecture

This repository generally follows a **Modular Monolith** pattern for its micro-projects. Utility scripts are typically self-contained. Adhere to the following principles:

*   **SOLID Principles:** Strive for Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code.
*   **YAGNI (You Ain't Gonna Need It):** Implement only what is necessary.
*   **Readability:** Write clear, maintainable code with appropriate comments and docstrings.

### 6. Reporting Issues

Before opening a new issue, please check if a similar issue already exists. Provide detailed information when reporting issues, including:

*   Project/Script Name
*   Python Version
*   Steps to reproduce
*   Expected vs. Actual behavior
*   Screenshots or error logs (if applicable)

### 7. Asking Questions

For general questions about the projects or how to use them, please use the GitHub Discussions feature if available, or open a well-defined issue tagged as a 'question'.

## 🤝 Thank You!

Your contributions are vital to the growth and quality of this project. We look forward to collaborating with you!

---*

*This document is dynamically generated. For specific technical directives, consult the `AGENTS.md` file and the project's `README.md`.*