# python-linting-formatting
This demo will show how to set up Black, Flake8, isort, and Git Hooks for automatic linting and formatting.

# Install dependencies

It is recommended that you use a virtual environment to install the dependencies. Below is a basic example of how to create a virtual environment, but `miniconda` or even a Docker container will work here as well.

## Automated Remote Installation


## Local Installation

### Create virtual environment
The following command will create a virtual environment called `.venv` in your current directory.

```
$ python3 -m venv .venv
```

### Activate the environment
The following commands activate an existing virtual environment on Windows and Unix systems. The command assume that the virtual environment is named venv and that its location is in a subdirectory path/to/ of the current directory.

```
# Windows (CMD.exe)
$ .venv\Scripts\activate.bat

# Unix
$ source .venv/bin/activate
```

Once activated your prompt should prepend the name of the virtual environment as shown below.

```
$ (venv) echo 'Hello, World!'
```

### Deactivate virtual environment
Use the following command to deactivate your virtual environment.

```
$ (venv) deactivate
```

### Install dependencies
After you activate your vitual environment, the following command will install the required dependencies.

```
$ (venv) pip install -r requirements
```