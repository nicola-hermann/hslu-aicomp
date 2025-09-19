# MAP_CSMM - HSLU AI Competition Package

A Python package developed for the HSLU AI Competition.

## Description

This package provides tools and utilities for the HSLU AI Competition. The project is structured as a proper Python package with modern tooling including `uv` for dependency management and `ruff` for code formatting and linting.

## Requirements

- Python 3.13 or higher
- [uv](https://docs.astral.sh/uv/) package manager

## Installation

First, install UV if you haven't already, then install the package using uv:

```bash
uv sync
```

This installs the correct python version alongside with the package and all its dependencies



### For Development

Packages are added with;
```bash
uv add package_name
```
This automatically updates the `pyproject.toml` and the `uv.lock` file

## Project Structure

```
hslu-aicomp/
├── src/
│   └── map_csmm/
│       ├── __init__.py
│       └── main.py
├── .vscode/
│   └── settings.json   # VS Code configuration
├── notebooks
│   └── submission_01.ipynb
├── scripts
│   └── test_script.py      # Scripts to run package code like e.g. training scripts
├── .gitignore
├── .python-version
├── pyproject.toml      # Project configuration with dependency groups
├── uv.lock            # Dependency lock file
└── README.md
```

## Development Tools

This project uses modern Python development tools:

- **[uv](https://docs.astral.sh/uv/)**: Fast Python package installer and resolver
- **[ruff](https://docs.astral.sh/ruff/)**: Fast Python linter and formatter
- **setuptools**: Build system

## VS Code Integration

The project includes VS Code settings (`.vscode/settings.json`) that:
- Configure Python formatting with ruff
- Enable format on save
- Set up proper linting
