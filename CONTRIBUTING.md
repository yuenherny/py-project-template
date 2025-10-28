# Contributing Guidelines

[!NOTE]
> Edit this document to suit your team's contribution process and standards.

## Development Setup

1. Fork and clone the repository
2. Set up your development environment:
    ```bash
    uv venv
    # Activate virtual environment
    # Windows:
    .venv\Scripts\activate
    # Unix/MacOS:
    source .venv/bin/activate
    # Install dependencies
    uv pip install -r .[dev,test]
    ```
3. Install pre-commit hooks:
    ```bash
    pre-commit install
    ```

## Code Standards

- Use `ruff` for code formatting and linting
- Apply type hints and use `mypy` for type checking
- Write tests for new features using `pytest`
- Maintain test coverage for your code
- Follow the project structure as outlined in [ARCHITECTURE.md](ARCHITECTURE.md)

## Pull Request Process

1. Create a new branch for your feature
2. Write clear, documented code with appropriate tests
3. Ensure all tests pass and pre-commit checks succeed
4. Update documentation as needed
5. Submit a pull request with a clear description of changes

## Documentation

- Update relevant documentation for any new features
- Follow the existing documentation style
- Include docstrings for new functions and classes
- Update README.md if adding new features or changing setup steps

## Questions

For questions or discussions about contributions, please open a GitHub issue.