# Différence entre git fetch et git pull ?

- **`git fetch`** : Récupère les dernières modifications depuis le dépôt distant sans les fusionner automatiquement avec la branche actuelle. Il met à jour uniquement les références locales des branches distantes.

- **`git pull`** : Récupère les dernières modifications depuis le dépôt distant et les fusionne automatiquement avec la branche actuelle, combinant ainsi les commandes `git fetch` et `git merge`.

# L'Histoire de "master" et de "main"

- **"master"** a été le nom par défaut de la branche principale dans Git depuis sa création en 2005, sans connotation sociale particulière.
- En 2020, suite aux mouvements sociaux et à un effort pour un langage plus inclusif, GitHub et d'autres plateformes ont adopté **"main"** comme nouveau nom par défaut pour la branche principale.
- Aujourd'hui, **"main"** est couramment utilisé pour les nouveaux projets, bien que certains dépôts plus anciens utilisent encore "master".

# Comprendre le dossier .git

Le dossier `.git` est crucial pour un dépôt Git, contenant les éléments nécessaires pour gérer l'historique et la configuration d'un projet. Voici les principaux fichiers et dossiers qu'il contient :

- **`HEAD`** : Pointeur vers la branche active actuelle.
- **`config`** : Configuration spécifique au dépôt (utilisateur, branches, etc.).
- **`description`** : Description du dépôt, utilisé par des interfaces comme GitWeb.
- **`index`** : Zone de transit (staging area) pour les changements avant commit.
- **`logs/`** : Journaux des déplacements de `HEAD` et des branches.
- **`objects/`** : Contient tous les objets Git (commits, arbres, blobs) sous forme compressée.
- **`refs/`** : Références aux branches, tags, et autres pointeurs vers des commits.
- **`info/`** : Informations supplémentaires, comme des exclusions de commit.
- **`hooks/`** : Scripts déclenchés par certains événements Git (ex: `pre-commit`).
- **`packed-refs`** : Fichier compressant les références pour optimiser l'accès.

Ces composants font de `.git` le cœur du suivi de version dans Git.

# Comprendre le fichier .gitignore

Le fichier `.gitignore` indique à Git quels fichiers ou dossiers ne doivent pas être suivis ou inclus dans le contrôle de version. Il est placé à la racine du dépôt ou dans des sous-dossiers spécifiques.

**Exemple :**

- Ignorer tous les fichiers temporaires créés par un éditeur de texte : *.tmp
- Ignorer les fichiers de configuration secrets : .env


