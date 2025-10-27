# Démarrer un repository

Cloner un repository :
``` bash 
git clone https://github.com/quentinlegay/gitsheet.git
```

Initialiser un repository :
``` bash 
git init
```

# Effectuer des changements

Ajoute tous les fichiers nouveaux ou modifiés du répertoire courant au suivi de Git, les préparant pour le prochain commit :
``` bash 
git add *
```

Enregistre les modifications suivies (staged) dans un nouveau commit avec un message "fix issue X", en ajoutant les modifications des fichiers déjà suivis (tracked) :
``` bash 
git commit -am "fix issue X"
```

Envoie les commits locaux au dépôt distant :
``` bash 
git push
```
# Travailler avec des branches
Création d'une nouvelle branche nommée featureA et bascule immédiatement sur celle-ci :
``` bash 
git checkout -b featureA
```

Récupérer les modifications depuis un dépôt distant et les fusionner avec la branche locale active.
```bash
git pull <remote> <branch>
```
Elle combine deux commandes Git en une :

1. **`git fetch`** : Récupère les nouveaux commits depuis le dépôt distant.
2. **`git merge`** : Fusionne les modifications récupérées avec la branche courante.

Créer une branche locale à partir d'une branche distante (Si par exemple vous voulez récupérer la branche distante feature/ma-branche)
```bash
git checkout -b feature/ma-branche origin/feature/ma-branche
```

# Checker son repository

Affiche l'état actuel du dépôt, montrant les modifications qui ont été faites et celles qui sont prêtes à être commises :
``` bash 
git status
```
