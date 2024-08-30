# semi-auto-git-commit
A semi-automatic git commit message crafter.

# Prerequisites
## Setup python virtual environment.
`python3 -m venv /dir/of/cloned/repo`

## Install openai python api library
`/dir/of/cloned/repo/bin/pip install openai`

## Have a git repo with staged files

# Setup
Create an shell alias.
`echo -e "\n# semi-auto-git-commit\nalias git-commit='/dir/of/cloned/semi-auto-git-commit/bin/python3 /dir/of/cloned/semi-auto-git-commit/main.py'" >> ~/.zshrc`

# Usage
Go into your git repo with staged files and run your alias or run the script itself!
