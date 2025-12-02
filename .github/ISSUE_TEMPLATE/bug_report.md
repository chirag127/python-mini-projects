---
name: Bug Report
about: Please report bugs here
title: "[Bug] "
labels: bug
assignees: "chirag127"

body:
  - type: markdown
    attributes:
      value: | # IMPORTANT: Ensure this links to your project and adheres to Apex standards.
        ## Bug Report
        Thank you for reporting a bug! Please provide as much detail as possible.

        **Project Repository:** [Python-Utility-Scripts-And-Micro-Projects-Collection](https://github.com/chirag127/Python-Utility-Scripts-And-Micro-Projects-Collection)
        **Apex Standards Version:** December 2025 / 2026 Edition

        *By submitting this report, you agree to adhere to the project's contribution guidelines and licensing.* 

  - type: input
    id: environment
    attributes:
      label: Environment Details
      description: 'Please specify the operating system, Python version, and any relevant library versions (e.g., `uv`, `ruff`, `pytest`).'
      placeholder: "e.g., macOS 14.2, Python 3.11.5, uv 0.1.15, ruff 0.2.2"
    validations:
      required: true

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: Steps to Reproduce
      description: 'Provide a clear, step-by-step guide to reproduce the behavior.'
      placeholder: |
        1. Go to '...' path.
        2. Run the command '...' with arguments '...'.
        3. Observe the error message or unexpected behavior.
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: Expected Behavior
      description: 'Describe what you expected to happen after following the steps above.'
      placeholder: "e.g., The script should output the processed data without errors."
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    attributes:
      label: Actual Behavior
      description: 'Describe what actually happened. Include any error messages, stack traces, or screenshots if applicable.'
      placeholder: "e.g., The script crashed with the following error..."
    validations:
      required: true

  - type: textarea
    id: additional_context
    attributes:
      label: Additional Context
      description: 'Add any other context about the problem here. For example, specific use cases, configuration details, or links to related issues.'
      placeholder: "(Optional)"
    validations:
      required: false

  - type: markdown
    attributes:
      value: | # IMPORTANT: This section reinforces AI Agent Directives and verification protocols.
        ## Verification and AI Agent Alignment

        When addressing this bug, please ensure adherence to the following:

        *   **AI Agent Directives:** Consult the project's `AGENTS.md` for specific AI interaction protocols and architectural constraints relevant to this bug.
        *   **Apex Principles:** Maintain Zero-Defect, High-Velocity, and Future-Proof development standards.
        *   **Testing:** Ensure adequate unit and/or integration tests are added or updated to cover the fix.
        *   **Linting/Formatting:** Verify code conforms to Ruff standards.

        If the bug involves AI model behavior, please refer to the **AI Integration** section in `AGENTS.md` for appropriate debugging steps.
