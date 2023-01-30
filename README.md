# python-linting-formatting
This demo will show how to set up Black, Flake8, isort, and Git Hooks for automatic linting and formatting.

## Automated Remote Installation

Similar to GitHub Codespaces, [Gitpod](https://www.gitpod.io) provides a remote VSCode developer environment.

Launch the demo environment using the link below.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/PDXPythonPirates/python-linting-formatting.git)

## Local Installation

### Create virtual environment

The following command will create a virtual environment called `.venv` in your current directory.

```bash
$ python3 -m venv .venv
```

### Activate the environment

The following commands activate an existing virtual environment on Windows and Unix systems. The command assume that the virtual environment is named venv and that its location is in a subdirectory path/to/ of the current directory.

```bash
# Windows (CMD.exe)
$ .venv\Scripts\activate.bat

# Unix
$ source .venv/bin/activate
```

Once activated your prompt should prepend the name of the virtual environment as shown below.

```bash
$ (venv) echo 'Hello, World!'
```

### Deactivate virtual environment

Use the following command to deactivate your virtual environment.

```bash
$ (venv) deactivate
```

### Install dependencies

After you activate your vitual environment, the following command will install the required dependencies.

```bash
$ (venv) pip install -r requirements
```
