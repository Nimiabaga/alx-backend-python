# 0x00. Python - Variable Annotations

**Author:** Julie Peters

This project involves learning and implementing type annotations in Python 3. The goals are to specify function signatures and variable types, understand duck typing, and validate the code with `mypy`.

## Requirements

- Python 3.7
- All files should end with a new line
- Use the pycodestyle style (version 2.5.0)
- All files must be executable
- All modules should have documentation
- All classes should have documentation
- All functions should have documentation

## Concepts

### Type Annotations in Python 3

Type annotations allow you to specify the expected data types of variables, function arguments, and return values. This improves code readability, maintainability, and helps catch potential bugs early.

Example:
```python
def add(a: int, b: int) -> int:
    return a + b

