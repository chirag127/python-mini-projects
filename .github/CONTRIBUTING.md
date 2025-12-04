# Contributing Guidelines for PyAccelerator-Python-Code-Toolkit-For-Developers

Thank you for considering contributing to the **PyAccelerator-Python-Code-Toolkit-For-Developers** repository! We aim to foster a collaborative environment for high-quality, production-ready Python utilities.

## 1. Our Pledge

In the interest of fostering an open and welcoming community, we, the maintainers and contributors, pledge to make participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation. We are committed to creating a positive and inclusive environment.

## 2. Code of Conduct

Our Code of Conduct can be found [here](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/blob/main/CODE_OF_CONDUCT.md).

## 3. How to Contribute

We welcome contributions in the form of bug reports, feature requests, documentation improvements, and code submissions.

### 3.1 Reporting Bugs

1.  **Search First:** Before reporting a bug, please check the [Issues](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/issues) to see if your issue has already been reported.
2.  **Reproducible Steps:** If your issue is not reported, please [open a new issue](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/issues/new?template=bug_report.md). Provide clear, concise steps to reproduce the bug. Include:
    *   The version of Python you are using.
    *   The operating system.
    *   Any relevant environment details.
    *   Code snippets or a minimal reproducible example if possible.

### 3.2 Suggesting Enhancements or New Features

1.  **Search First:** Check existing [Issues](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/issues) to see if your idea has already been discussed.
2.  **Open an Issue:** If your idea is new, please [open a new issue](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/issues/new?template=feature_request.md) with a detailed description of the proposed enhancement.

### 3.3 Contributing Code

1.  **Fork the Repository:** Start by forking the [PyAccelerator-Python-Code-Toolkit-For-Developers](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers) repository to your GitHub account.
2.  **Clone Your Fork:** Clone your forked repository locally:
    bash
    git clone https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers.git
    cd PyAccelerator-Python-Code-Toolkit-For-Developers
    
3.  **Set Up Development Environment:**
    *   Ensure you have Python 3.10+ installed.
    *   Use `uv` for managing dependencies:
        bash
        uv venv
        source .venv/bin/activate
        uv pip install --editable ".[dev]"
        
4.  **Create a New Branch:** Create a descriptive branch for your changes:
    bash
    git checkout -b feature/your-feature-name # or bugfix/your-bug-fix
    
5.  **Make Your Changes:** Implement your bug fixes or new features. Follow the project's coding standards and principles (SOLID, DRY, YAGNI).
6.  **Run Tests:** Ensure all tests pass. The project uses `Ruff` for linting and `Pytest` for testing.
    bash
    ruff check .
    pytest
    
7.  **Update Documentation:** If your changes affect documentation, please update the relevant files (e.g., README, docstrings).
8.  **Commit Your Changes:** Commit your changes with clear and concise commit messages.
    bash
    git add .
    git commit -m "feat: Add descriptive commit message"
    
9.  **Push to Your Fork:** Push your branch to your fork on GitHub:
    bash
    git push origin feature/your-feature-name
    
10. **Open a Pull Request:** Go to the original repository and open a new pull request from your branch. Provide a clear description of your changes.

### 3.4 Pull Request Process

*   All pull requests will be reviewed by the maintainers.
*   Please ensure your code adheres to the established coding style and passes all automated checks (linting, tests).
*   Be prepared to make changes based on feedback.

## 4. Architectural Principles & AI Agent Directives

This project adheres to **Apex Technical Authority** standards, emphasizing Zero-Defect, High-Velocity, and Future-Proof development.

*   **Architecture:** Primarily **Modular Monolith** for clear separation of concerns.
*   **Python Toolchain:** Python 3.10+, **uv** for dependency management, **Ruff** for linting/formatting, **Pytest** for testing.
*   **AI Integration:** Leverages **Google Gemini API** (`gemini-3-pro` by default) for intelligent automation.
*   **CLI Framework:** Utilizes `Click` for a robust command-line interface.

For detailed AI Agent Directives and specific commands, please refer to the [AGENTS.md](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/blob/main/AGENTS.md) file.

## 5. Licensing

This project is licensed under the **CC BY-NC** license. See the [LICENSE](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/blob/main/LICENSE) file for details.

