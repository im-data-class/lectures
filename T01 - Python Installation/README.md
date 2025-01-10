# System-Wide Installation

## Installation - Windows

- Install `python 3.12` from microsoft store.

## Installation - Mac

- Open terminal
  - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
`
  - `brew install python`
- [Source](https://mac.install.guide/homebrew/3)

## Update Scripts Path Variables

### Windows

- `python -c 'import os,sysconfig;print(sysconfig.get_path("scripts",f"{os.name}_user"))'`

### Mac

- In `~/.bashrc`
  - `export PATH="$PATH:...."`

## Install packages

- `pip install jupyterlab ipykernel pandas matplotlib seaborn openpyxl ruff`
  - (Or) `python -m pip install ...`

## Install VSCode extensions

- Python Extension Pack
- Jupyter
- Ruff
