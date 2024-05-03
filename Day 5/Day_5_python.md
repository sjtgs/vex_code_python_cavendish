<!-- Content Developed by Joshua Chipile  -->

# Python Day 5

#### Pytest

- Install Pytest and Coverage

```
pip install pytest-cov
```

```
pip install -U pytest
```

- Check version pytest

```
$ pytest --version
pytest 8.1.1
```

```python
# calculator.py

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y
```

- Write tests for these functions using pytest in a separate file test_demo.py:

```python
# test_demo.py

import calculator

def test_add():
    assert calculator.add(3, 5) == 8
    assert calculator.add(-1, 1) == 0

def test_subtract():
    assert calculator.subtract(5, 3) == 2
    assert calculator.subtract(1, -1) == 2

```

- Run these tests using pytest, you can simply execute the following command in your terminal.

```
pytest test_demo.py
```

#### Pylint and PEP8

- Pylint and PEP8 are tools and style guidelines used in Python development to enforce code quality and maintainability.

1. **Pylint**:
   - Pylint is a static code analysis tool that checks Python code for errors, potential bugs, and adherence to coding standards.
   - It evaluates code against a set of predefined coding standards and generates reports with suggestions for improvements.
   - Pylint assigns a score to your code based on its adherence to the Pylint conventions.
   - It checks for various aspects of code quality, including syntax errors, unused variables, missing docstrings, and more.
   - Install Pylint

   ```
   pip install pylint
   ```

   - Example usage:

     ```
     pylint calc.py
     ```

2. **PEP8**:
   - PEP8 is the official style guide for Python code, which provides guidelines for writing clean, readable, and consistent Python code.
   - It covers various aspects of coding style, including indentation, naming conventions, line length, imports, and more.
   - Adhering to PEP8 guidelines improves code readability and makes it easier for other developers to understand and maintain your code.
   - PEP8 is not enforced by Python itself, but there are tools like `flake8` that can be used to check code against PEP8 standards.
   - Install flake8

   ```
    pip install flake8
   ```

   - Example usage with `flake8`:

     ```
     flake8
     ```

- Both Pylint and PEP8 are valuable tools for maintaining high code quality and consistency in Python projects. By using these tools and adhering to their recommendations, developers can produce cleaner, more maintainable code that is easier to understand and collaborate on.

<!-- Content Developed by Joshua Chipile  -->