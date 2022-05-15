---
id: 5AA8KKYfUpbCkcdm7CaMX
title: Virtual Environment
desc: ''
updated: 1652655107454
created: 1639626240928
---
# Python Virtual Environments

ref:
- [Yury Zhauniarovich | Configuring Python Workspace](https://zhauniarovich.com/post/2020/2020-02-configuring-python-workspace/) 
- [Real Python](https://realpython.com/python-virtual-environments-a-primer/)
- [opensource | guide with virtualenvwrapper](https://opensource.com/article/21/2/python-virtualenvwrapper)

By default, every project on your system will use the same directories to store and retrieve site packages (third party libraries). A `virtual environment` enables us to keep the dependencies required by different projects in separate places, by creating virtual Python environments.

The main purpose of Python virtual environments is to create an isolated environment for Python projects. This means that each project can have its own dependencies, regardless of what dependencies every other project has.

Python workspace management can be split into two phases:
1. Python interpreter versions management
    - tool to use: [[pyenv|notes.tutorial.python.virtual-environment.pyenv]]
    - reason: because some tools require specific version of the Python interpreter to run
2. Package dependencies management
    - tool to use: [[poetry|notes.tutorial.python.virtual-environment.poetry]], [[virtualenvwrapper|notes.tutorial.python.virtual-environment.virtualenvwrapper]]
    - reason: 
        - If you install dependencies globally all the time, it may lead to some issues. For instance, one package may update the library that the second package depends on. If old and new versions are incompatible (e.g., the new version of the library removes some deprecated functionality that the second package uses) this will make the second package unusable. The default package manager, `pip`, does not resolve dependencies well
        - In order to reduce the probability of such events, it is better to isolate each package installing into the isolated environment the libraries with correct versions the project depends on

## Thoughts

### Where should I put virtual environment folder?

- [[virtualenvwrapper|notes.tutorial.python.virtual-environment.virtualenvwrapper]] keeps all your environments in one place `~/.virtualenvs` by default
- Similar default behavior with [[poetry|notes.tutorial.python.virtual-environment.poetry]]
    ![[Jupyter in Poetry|notes.tutorial.python.virtual-environment.poetry.jupyter-in-poetry#^gaqhf9yjjqhs]]
- This setup depends on personal taste. Others will prefer that the project's virtual environment folder is located inside their project's folder
- VS Code, which I use for Python development, cannot automatically select the right virtual environment if they are all stored in one place
    -  However, it can automatically activate the environment if it is stored in the `.venv` directory inside your project `root`

## Related resources

- [Stackoverflow | What is the difference between venv, pyvenv, pyenv, virtualenv, virtualenvwrapper, pipenv, etc?](https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe)
- [Liquid Web | setup Python Virtual Environment on Windows 10](https://www.liquidweb.com/kb/how-to-setup-a-python-virtual-environment-on-windows-10/)
- [Ruslanmv | setup Python Virtual Environment in WSL](https://ruslanmv.com/blog/Python3-in-Windows-with-Ubuntu)
- [Analyzing Alpha | Python Virtual Environments: Setup & Usage](https://analyzingalpha.com/python-virtual-environment)