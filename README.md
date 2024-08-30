# semi-auto-git-commit
A semi-automatic git commit message crafter.

# Prerequisites

## Clone the repo

## Setup python virtual environment.
`python3 -m venv /dir/of/cloned/repo`

## Install openai python api library
`/dir/of/cloned/repo/bin/pip install openai`

## Have a git repo with staged files

# Setup
Create an shell alias.
Add to your .zshrc or .bashrc file something like the following.
```
# semi-auto-git-commit
alias git-commit='/path/to/venv/bin/python3 /path/to/venv/main.py'
```

# Usage
Go into your git repo with staged files and run your alias!
