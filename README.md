# Information Security Hub

Documentation that assists with learning security operations

## Development

Create a python virtualenvironment, activate it and install dependencies

```
virtualenv venv
source venv/bin/activate
pip install pip-tools
pip-compile && pip-sync
```

Serve the site locally, edit the markdow files as required.

```
mkdocs serve
```

## Testing workflows locally

Install Nektos Act
https://github.com/nektos/act

```
curl -s https://raw.githubusercontent.com/nektos/act/master/install.sh | sudo zsh
```
