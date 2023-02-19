# Recommended practice for managing Python Environments

A Python virtual enviroment contains of both the Python interpreter (e.g. Python 3.10 or Python 3.11) and a folder containing the installed libraries.
It's a recommended practice to use a seperate Python virtual environment for every Python project. Furthermore is is recommended to define your dependencies in a `requirements.txt` file.

Within (each of) your Python Project(s) create a new folder `.venv` for the Python virtual enviroment

```cmd
mkdir .venv
```

To create the Python virtual enviroment you can run the following command

```cmd
python -m venv .venv
```

Activate the Python virtual enviroment

```cmd
.\.venv\Scripts\activate
```
