# Python

## Initialization sequence

1. Install Python
1. Install GitHub CLI
1. Connect to h111359 GitHub account
1. Clone locally h111359/python repository
1. Create virtual environment
1. Activate virtual environment
1. Install requirements file
1. Run jupyter notebook



## Install Python

Official Python site:

[https://www.python.org/](https://www.python.org/)

## For installing GitHub CLI on Linux:

https://docs.github.com/en/get-started/using-github/github-cli

https://docs.github.com/en/github-cli

https://docs.github.com/en/github-cli/github-cli/quickstart

https://github.com/cli/cli#installation

https://github.com/cli/cli/blob/trunk/docs/install_linux.md


## Working with GitHub CLI
First ensure that you are logged to GitHub:

    gh auth login


To clone a repo:

    gh repo clone h111359/python


## Virtual Environment

### Creation of virtual environment

First create a folder where all virtual environments will reside.
Add a row in .gitignore file with the name of the folder so it to be excluded from the repo.
Then create a virtual environmen in this folder

Linux:

    python3 -m venv <virtual environment name>

    cd ./venv && python3 -m venv fdmt

### Activation of Virtual environment

Linux:

    source <path to the environment>/bin/activate

    source ./venv/bin/activate

Windows:

    <path to the environment>\Scripts\activate.bat


Deactivation:

    deactivate 

### Install requirements file

    pip install -r requirements.txt

    pip install -r "./fundamentals/course_materials/python-fundamentals-main/02 - Installing and Running Python/requirements.txt"


### Run jupyter notebook

    jupyter notebook

## Additional links to documentation

https://docs.python.org/3.10/tutorial/index.html

https://docs.python.org/3.10/index.html

https://docs.python.org/3.10/using/windows.html