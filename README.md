# Cookiecutter Python Template
My personal template for projects.
It looks much like [python-best-practices-cookiecutter](https://github.com/sourcery-ai/python-best-practices-cookiecutter) with some differences.
The main difference is that here's ***no isort feature***. I don't like the idea of sorting imports *alphabetically*.

# Features
- **Black** for formatting
- **Flake8** for PEP8 correspondance check
- **Mypy** for static typing 
- **Pytest** for testing
- **Dockerfile** for containerization
- **Pre-commit** with Git hooks

# Usage
Install **pipenv** and **cookiecutter** (make sure that it'll be located in a PATH directory):
```sh
pip install pipenv cookiecutter
```
Use cookiecutter to create a new project:
```sh
cookiecutter https://github.com/Ors1mer/Cookiecutter_python_template/
```
And install all dev modules using pipenv:
```sh
pipenv install --dev
```
Switch to the environment:
```sh
pipenv shell
```

# Ready to go!
