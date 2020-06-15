# EASE Fall School - Day 3


## Prerequisites

* Python 2.7
* Pipenv (https://pypi.org/project/pipenv/)

#### Ubuntu
```
sudo apt update
# Install pip
sudo apt install python-pip
# Install pipenv
pip install --user pipenv
```
#### MacOS
```
# Install pipenv
brew install pipenv
```
#### Windows
Make sure to have Python 2.7 installed. Download the [pip installer script](https://bootstrap.pypa.io/get-pip.py). Then open the CMD and navigate to the downloaded script.
```
:: Install pip package manager
python get-pip.py
:: Install pipenv
pip install --user pipenv
```

## Installing

1. Open a terminal
2. Go into the cloned repo (either download the repo as zip or clone with git.)
3. Execute `pipenv install`
4. Afterwards execute `pipenv install jupyter`

## Starting the exercises

1. Open a terminal
2. Go into the cloned repo
3. Execute `pipenv shell`
4. Afterwards execute `jupyter notebook`
5. A browser should open the link which is shown in the terminal
6. Open the *Exercises.ipynb* notebook
