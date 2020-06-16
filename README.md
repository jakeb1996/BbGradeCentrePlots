# Blackboard Grade Centre Plots

Just for fun...

## Getting Started

Ensure that you have the minimal software installed:

- Python 3.8

- VirtualEnv

- Pip


## Running the notebook

1. Clone this repo

```
git clone https://github.com/jakeb1996/BbGradeCentrePlots.git
```

2. Create the virtual environment and install dependencies from pip

On Windows (with Windows Python Launcher installed):

```
py -3 -m venv .venv

.venv\Scripts\activate.bat

pip install -r requirements.txt
```

On Unix:

```
py -3 -m venv .venv

source .venv/bin/activate

pip install -r requirements.txt
```

3. Run Jupyter

```
jupyter notebook
```

4. Follow the instructions in the notebook


## Useful Documentation

- [Python3 - using venv](https://docs.python.org/3/tutorial/venv.html)

- [Py Launcher for Windows](https://docs.python.org/3/using/windows.html?highlight=shebang#python-launcher-for-windows)


## Contributing

Contributions are welcome.

It's prefered that if you're making changes, these are done in your own branch.

When you're happy with the change, create a pull request into master.

When making changes to the environment, make sure that you export the changes to the yaml file

```
pip freeze > requirements.txt
```

## Licence

See LICENSE