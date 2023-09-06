![Python](https://img.shields.io/badge/python-3.10-blue.svg)

![CI](https://github.com/BrandwatchLtd/python_template/actions/workflows/CI.yml/badge.svg)

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)
[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/BrandwatchLtd/python_template)

# Spaceship Titanic Kaggle Competition
[Link to the Kaggle competition](https://www.kaggle.com/competitions/spaceship-titanic/overview )

## Info about the Python Template
This repository provides a starter skeleton of a python project that adopts some basic best practices
* Use `poetry` for dependency resolution, virtualenv management, packaging
* `src` package layout
* Code Formatting with `ruff` and `black`
* Code linting with `ruff` and `mypy`
* Test framework with `pytest`
* Test coverage metrics with `coverage.py`
* Continuous Integration with Github Actions (pull requests and `main`)
* Makefile task runner
* Separate `notebooks/` directory separate from packaged python code
* VSCode configuration for creating development environmentin Docker or on CodeSpaces
