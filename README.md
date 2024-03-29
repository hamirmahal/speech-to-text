# Setup

Run

```
python3 -m venv env/
pip list
pip install mypy
pip list
pip freeze > requirements.txt # Ensure we have the latest version of `mypy`.
```

in your terminal.

Then, restart your terminal or run

```
source env/bin/activate
```

# Installation

Run

```
pip list
pip install -r requirements.txt
pip list
```

in your terminal to install any packages in `requirements.txt`.

To install a new package, run

```
pip list
pip install mypy # replace `mypy` with the package name
pip list
pip freeze > requirements.txt
```

in your terminal.

# Running the Program

Run

```
time python src/main.py
```

in your terminal after activating the virtual environment.

# Testing and Type Checking

Run

```
time mypy . && time python -m unittest src.utils.print_with_time
```
