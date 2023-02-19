# excribe-docs

This repository contains contains several useful how-tos or tutorials as markdown files which can be served with the existing mkdocs setup and will be the basis for docs.excribe.dev

## Getting started

### Setup a Python virtual enviroment

Create a new folder `.venv`for the Python virtual enviroment

```cmd
mkdir .venv
```

Create the Python virtual enviroment

```cmd
python -m venv .venv
```

Activate the Python virtual enviroment

```cmd
.\.venv\Scripts\activate
```

### Install MkDocs and serve the documentation page

Install mkdocs and other requirements

```cmd
python -m pip install -r requirements.txt
```

Serve the documentation page

```cmd
mkdocs serve
```

Open the page on http://localhost:8000/
