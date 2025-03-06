# cicid-tempy

![Tests](https://github.com/MhdMartini/pytemplate/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11-blue?logo=python&logoColor=white)
![Checked with mypy](https://img.shields.io/badge/mypy-checked-blue)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/MhdMartini/pytemplate/blob/main/.pre-commit-config.yaml)
![MkDocs Material](https://img.shields.io/badge/MkDocs-Material-lightgrey?logo=materialdesign)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Using uv](https://img.shields.io/badge/using-uv-blue?logo=python)
[![semantic-release: conventional](https://img.shields.io/badge/semantic--release-conventional-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)


Python project template that tries to automate CI/CD best practices.

Currently, only Trunk-based development pattern is supported.

Features out of the box:
1. pre-commit hooks:
    - Linting and formatting with `ruff`
    - `codespell`
    - `uv` dependency sync
    - Conventional commit message check with `commitizen`
2. Github workflows:
    - Pre-commit hooks
    - Testing
    - Versioned documentation website building and publishing with `mkdocs-material` and `mike`.
    - Package building and publishing to `PyPi`
    - Automatic semantic releases and changelog updates
