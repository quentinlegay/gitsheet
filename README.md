# Gitsheet

This is the repository of https://quentinlegay.github.io/gitsheet.

This website is built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## How to contribute?

### Clone the repository

```
git clone https://quentinlegay.github.io/gitsheet
cd gitsheet
```
### Install dependancies

```
pip install -r requirements.txt
```

### Running the website locally

```
mkdocs serve
```

http://127.0.0.1:8000/

### Deploy with docker

soon !

## Roadmap

- add infos about local/global config:
    - git config --local --get user.name
    - git config --local --get user.email

- Git trunk

- Squash commit

- Add vscode extension

- Complete "Echange de clé ssh", type de clé supporté par les solution git distant (Azure Devops, Github)

- https://learn.microsoft.com/fr-fr/windows-server/identity/ad-cs/pki-design-considerations

- Add liste git distant SaaS, Onprem, Souverain, light...

- Add info authent ( Git Credential Manager (GCM) etc https://learn.microsoft.com/en-us/azure/devops/repos/git/auth-overview?view=azure-devops)

- Add commit verify/signed

