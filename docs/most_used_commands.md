# Level 1

Cloner un repository :
``` bash 
git clone https://github.com/quentinlegay/gitsheet.git
```

Ajoute tous les fichiers nouveaux ou modifiés du répertoire courant au suivi de Git, les préparant pour le prochain commit :
``` bash 
git add *
```

Enregistre les modifications suivies (staged) dans un nouveau commit avec un message "fix issue X", en ajoutant les modifications des fichiers déjà suivis (tracked) :
``` bash 
git commit -am "fix issue X"
```

Affiche l'état actuel du dépôt, montrant les modifications qui ont été faites et celles qui sont prêtes à être commises :
``` bash 
git status
```

Envoie les commits locaux au dépôt distant : 
``` bash 
git push
```

# Level 2 
Création d'une nouvelle branche nommée featureA et bascule immédiatement sur celle-ci :
``` bash 
git checkout -b featureA
```

# Level 3