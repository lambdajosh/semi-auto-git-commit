# semi-auto-git-commit
A semi-automatic git commit message crafter.

This should be compatible with all API endpoints that follow the [OpenAI OpenAPI Spec](https://github.com/openai/openai-openapi):
* OpenAI
* Lambda.chat

# Prerequisites

## 1. Clone the repo

## 2. Setup environment variables
```
SEMI_AUTO_API_KEY=<API_KEY>
SEMI_AUTO_API_URL=<API_URL>
SEMI_AUTO_API_MODEL=<API_MODEL>
```

## 3a. Manual python virtual environment Setup

1. Setup python virtual environment.
    - `python3 -m venv /dir/of/cloned/repo`

1. Install openai python api library
    - `/dir/of/cloned/repo/bin/pip install openai`
    - `/dir/of/clone/repo/bin/pip install halo`

## 3b. Tox python virtual environment
You can forgo the previous 2 steps and have tox create the venv and install the dependencies for you.

Run `tox -e venv` in the root of this repo.

## 4. Have a git repo with staged files

# Setup
Create an shell alias.
Add to your .zshrc or .bashrc file something like the following.
```
# semi-auto-git-commit
alias git-commit='/path/to/venv/bin/python3 /path/to/venv/main.py'
```

# Usage
Go into your git repo with staged files and run your alias!
