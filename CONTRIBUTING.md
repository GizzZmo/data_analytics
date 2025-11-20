# Contributing to Data Analytics Project Template

First off, thank you for considering contributing to this project! It's people like you that make this template better for everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Pull Requests](#pull-requests)
- [Development Setup](#development-setup)
- [Style Guidelines](#style-guidelines)
  - [Python Style Guide](#python-style-guide)
  - [Jupyter Notebook Guidelines](#jupyter-notebook-guidelines)
  - [Git Commit Messages](#git-commit-messages)

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed and what you expected**
- **Include screenshots** if relevant
- **Include your environment details** (OS, Python version, conda version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested enhancement
- **Provide specific examples** to demonstrate the use case
- **Explain why this enhancement would be useful** to most users

### Pull Requests

1. Fork the repository and create your branch from `main`
2. If you've added code that should be tested, add tests
3. Ensure your code follows the project's style guidelines
4. Update the documentation if needed
5. Make sure your code lints without errors
6. Issue the pull request with a clear description

## Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/GizzZmo/data_analytics.git
   cd data_analytics
   ```

2. **Install Conda** (if not already installed)
   - Follow the [official instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

3. **Create a virtual environment** (recommended)
   ```bash
   conda create -n data_analytics python=3.10
   conda activate data_analytics
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Install development dependencies** (for linting and testing)
   ```bash
   pip install flake8 pylint black jupyter nbconvert
   ```

## Style Guidelines

### Python Style Guide

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide
- Use 4 spaces for indentation (no tabs)
- Maximum line length of 127 characters
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Run `flake8` and `pylint` before committing

Example:
```python
def process_data(df, column_name):
    """
    Process data by performing transformation on specified column.
    
    Args:
        df (pandas.DataFrame): Input dataframe
        column_name (str): Name of the column to process
    
    Returns:
        pandas.DataFrame: Processed dataframe
    """
    # Your code here
    pass
```

### Jupyter Notebook Guidelines

- Clear all outputs before committing (use `Cell > All Output > Clear`)
- Use markdown cells to explain your analysis
- Keep cells focused and not too long
- Add comments in code cells
- Use meaningful variable names
- Structure notebooks with clear sections using markdown headers

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line
- Consider starting the commit message with an applicable emoji:
  - 🎨 `:art:` - Improving structure/format
  - ⚡️ `:zap:` - Improving performance
  - 🐛 `:bug:` - Fixing a bug
  - 📝 `:memo:` - Adding or updating documentation
  - ✨ `:sparkles:` - Adding a new feature
  - 🔧 `:wrench:` - Adding or updating configuration files

## Questions?

Feel free to open an issue with your question or reach out to the maintainers.

Thank you for contributing! 🎉
