# Python Testing Project

## Overview

This project focuses on building a solid understanding of unit and integration testing in Python. You'll explore various testing patterns, such as mocking, parametrization, and fixtures, while working with Python's `unittest` framework.

## Resources

Before getting started, make sure to review the following resources:

- [unittest — Unit testing framework](https://docs.python.org/3/library/unittest.html)
- [unittest.mock — mock object library](https://docs.python.org/3/library/unittest.mock.html)
- [How to mock a readonly property with mock?](https://stackoverflow.com/questions/3209233/how-to-mock-a-readonly-property-with-mock)
- [parameterized](https://pypi.org/project/parameterized/)
- [Memoization](https://en.wikipedia.org/wiki/Memoization)

## Learning Objectives

By the end of this project, you should be able to:

- Differentiate between unit and integration tests.
- Understand and apply common testing patterns, including mocking, parametrization, and fixtures.

## Requirements

Please ensure that your project meets the following requirements:

- All code will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7.
- All files should end with a new line.
- The first line of all your Python files should be exactly `#!/usr/bin/env python3`.
- A `README.md` file at the root of the project folder is mandatory.
- Your code must adhere to the `pycodestyle` style guide (version 2.5).
- All files must be executable.
- All modules should include documentation that can be retrieved with `python3 -c 'print(__import__("my_module").__doc__)'`.
- All classes should include documentation that can be retrieved with `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`.
- All functions (inside and outside classes) should include documentation that can be retrieved with `python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`.
- Documentation should be a real sentence explaining the purpose of the module, class, or method.
- All functions and coroutines must be type-annotated.

## Required Files

The following files are required to complete this project:

- `utils.py`
- `client.py`
- `fixtures.py`

Please download and include these files in your project directory.

## Getting Started

1. Clone this repository to your local machine.
2. Install any necessary dependencies.
3. Review the provided files and ensure that you understand the structure and purpose of each.
4. Implement the required tests and ensure that they pass according to the project specifications.

## Testing

To run the tests, use the following command:

```bash
python3 -m unittest discover


