# Python Project Template

A template for Python projects with a standard structure and configurations for developing in VS Code and GitHub Copilot.

## Features

- Standard Python project structure
- Virtual environment management with `uv`
- VS Code debugging configurations for FastAPI and pytest
- Development tools setup with `pre-commit`, `ruff`, and `mypy`
- AI-assisted coding with GitHub Copilot

## Getting Started

1. Clone this template
2. Create a virtual environment:
    ```bash
    uv venv
    ```
3. Activate the virtual environment:
    - Windows: `.venv\Scripts\activate`
    - Unix/MacOS: `source .venv/bin/activate`
4. Install dependencies:
    ```bash
    uv pip install -r .[dev,test]
    ```

## Architecture

See [ARCHITECTURE.md](ARCHITECTURE.md) for details on the project structure and design decisions.

## Contribution Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) for coding standards and contribution procedures.
