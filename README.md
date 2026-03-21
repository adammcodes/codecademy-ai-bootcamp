# ai-bootcamp

This project folder is for saving notebook files and Python practice examples from bootcamp.

## Purpose

I am using this repository to:

- save `.ipynb` notebook files
- practice beginner Python concepts
- keep bootcamp exercises in one place
- run notebooks locally in VS Code using a virtual environment

## Topics I am practicing

Some of the Python basics I am working on include:

- keywords
- variables
- data types
- operators such as `+`, `-`, `*`, `**`, `//`

## Project structure

```text
ai-bootcamp/
├── .venv/
├── notebooks/
├── practice/
├── README.md
└── .gitignore
```

## Virtual environment

This project uses a Python virtual environment so packages do not get installed into the system Python.

Create the virtual environment:

```sh
python3 -m venv .venv
```

Activate the virtual environment:

```sh
source .venv/bin/activate
```

When the virtual environment is active, the terminal usually shows `(.venv)`.

Deactivate the virtual environment:

```sh
deactivate
```

Install notebook support — to run Jupyter notebooks locally in VS Code, install ipykernel inside the virtual environment:

```sh
python -m pip install ipykernel
```

### Important note about .venv

The `.venv` folder can live inside this project folder, but it should not be committed to Git. Add this to `.gitignore`:

```text
.venv/
```

## Git and virtual environments

- My Git repository should track my code, notebooks, and notes
- My virtual environment should stay local on my machine
- Other people can recreate the virtual environment themselves

## Running notebooks in VS Code

After creating and activating the virtual environment:

1. Open the project folder in VS Code
2. Open the `.ipynb` notebook
3. Select the Python interpreter from `.venv`
4. Run notebook cells locally

## Notes

This repo is mainly for learning, experimenting, and keeping my bootcamp practice organized.
