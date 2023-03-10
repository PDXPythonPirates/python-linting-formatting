# python-linting-formatting

This is the starter repo for a demo that will show how to use Black, Flake8, isort, and Git Hooks for automatic linting and formatting.

This repo should not be used directly. Instead, [fork this repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo) and clone your copy instead.

## Automated Gitpod Installation

Navigate to `gitpod.io#https://github.com/[YOUR_GITHUB_USERNAME]/python-linting-formatting`. Once you create an account, your workspace should be configured automatically.

## Local Installation

### Create a virtual environment

The following command will create a [virtual environment](https://docs.python.org/3/library/venv.html) called `.venv` in your current directory.

```bash
$ python3 -m venv .venv
```

### Activate the environment

The following commands activate an existing virtual environment on Windows and Unix systems. The command assumes that the virtual environment is named `.venv`.

```bash
# Windows (CMD.exe)
$ .venv\Scripts\activate.bat

# Unix
$ source .venv/bin/activate
```

Once activated, your prompt should prepend the name of the virtual environment, as shown below.

```bash
$ (venv) echo 'Hello, World!'
```

### Deactivate virtual environment

Use the following command to deactivate your virtual environment.

```bash
$ (venv) deactivate
```

### Install dependencies

After you activate your virtual environment, the following command will install the required dependencies.

```bash
$ (venv) pip install -r requirements
```
