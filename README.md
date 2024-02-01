# NoSQL Data Visualisation Script

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

Visualises dummy NoSQL data of the following types:
- Document Databases
- Key-Value Stores
- Graph Data (Neo4j,etc)


## Getting Started <a name = "getting_started"></a>

Make sure to have poetry installed and a python interpreter of the correct version.

### Prerequisites

If you are using Arch Linux, you can install it in the following manner

```bash
yay -S python-poetry
```

You can also install it using the command below 

```bash
pipx install poetry
```

### Installing

Run the following commands to setup the dependencies

```bash
python3 -m venv .venv
poetry install --no-root
```
To run the notebook pick the '.venv' environment