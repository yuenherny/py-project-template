---
description: 'Python coding conventions and guidelines'
applyTo: '**/*.py'
---

# Python Coding Conventions

## Python Instructions

- Write clear and concise comments for each function.
- Ensure functions have descriptive names and include type hints for parameters and return types.
- Provide docstring following [Google Style Guide](https://google.github.io/styleguide/pyguide.html).
- Break down complex functions into smaller, more manageable functions.
- Avoid classes unless necessary; prefer functions for simpler tasks.

## General Instructions

- Always prioritize readability and clarity.
- For algorithm-related code, include explanations of the approach used.
- Write code with good maintainability practices, including comments on why certain design decisions were made.
- Handle edge cases and write clear exception handling.
- For libraries or external dependencies, mention their usage and purpose in comments.
- Use consistent naming conventions and follow language-specific best practices.
- Write concise, efficient, and idiomatic code that is also easily understandable.
- Use `ruff` for linting and formatting. Configuration is provided in [ruff.toml](../../ruff.toml) and guidelines in [CONTRIBUTING.md](../CONTRIBUTING.md).
- Use `mypy` for type checking. Configuration is provided in [pyproject.toml](../../pyproject.toml) and guidelines in [CONTRIBUTING.md](../CONTRIBUTING.md).

## Code Style and Formatting

- Follow the **PEP 8** style guide for Python.
- Maintain proper indentation (use 4 spaces for each level of indentation).
- Ensure lines do not exceed 79 characters.
- Place function and class docstring immediately after the `def` or `class` keyword.
- Use blank lines to separate functions, classes, and code blocks where appropriate.

## Edge Cases and Testing

- Always include test cases for critical paths of the application.
- Account for common edge cases like empty inputs, invalid data types, and large datasets.
- Include comments for edge cases and the expected behavior in those cases.
- Write unit tests for functions and document them with docstring explaining the test cases.

## Example of Proper Documentation

```python
def calculate_area(radius: float) -> float:
    """
    Calculate the area of a circle given the radius.
    
    Parameters:
        radius (float): The radius of the circle.
    
    Returns:
        float: The area of the circle, calculated as π * radius^2.
    """
    import math
    return math.pi * radius ** 2
```