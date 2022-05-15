---
id: noikg9qekz2t74b0mmfwh39
title: Poetry
desc: ''
updated: 1652606580391
created: 1652606285505
---
# [Poetry](https://python-poetry.org/)

ref: [jayway](https://blog.jayway.com/2019/12/28/pyenv-poetry-saviours-in-the-python-chaos/)

`Poetry` is a packaging and dependency manager. It resolves your library dependencies. It can also build and publish your project.

The main file of your poetry project is the `pyproject.toml` file
    - the requirements, the dev-requirements and project metadata are defined in this file
    - poetry uses the `.toml` file to resolve the dependencies of your defined requirements, and creates the `poetry.lock` file 
    - poetry then creates a virtual environment and installs everything from the `.lock` file.

Some alternatives to poetry for virtual environments are virtualenv, conda, venv or pipenv