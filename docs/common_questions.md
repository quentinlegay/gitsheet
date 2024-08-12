# Différence entre git fetch et git pull ?

- **`git fetch`** : Récupère les dernières modifications depuis le dépôt distant sans les fusionner automatiquement avec la branche actuelle. Il met à jour uniquement les références locales des branches distantes.

- **`git pull`** : Récupère les dernières modifications depuis le dépôt distant et les fusionne automatiquement avec la branche actuelle, combinant ainsi les commandes `git fetch` et `git merge`.

# Histoire des termes "master" et "main" dans Git

1. Origine du terme "master"

**"master"** a été le nom par défaut de la branche principale lors de la création d'un nouveau dépôt Git depuis sa création en 2005. Ce nom a été choisi pour désigner la branche principale ou "master" branch, d'où d'autres branches peuvent être dérivées. Le terme n'avait initialement aucune connotation sociale ou historique particulière et était couramment utilisé dans le développement logiciel.

2. Transition vers "main"

- Au fil du temps, des préoccupations ont émergé concernant l'utilisation du terme "master" en raison de ses associations historiques avec l'esclavage, même si dans ce contexte spécifique, "master" se réfère plutôt à l'idée de "maître" dans le sens technique (maître-esclave en technologie).

- En 2020, suite aux mouvements sociaux autour de Black Lives Matter, la communauté technologique a pris conscience de l'importance de la terminologie inclusive. Plusieurs organisations et projets ont décidé de changer le nom par défaut de la branche principale de "master" à **"main"** pour éviter toute connotation négative et promouvoir un langage plus inclusif.

3. Adoption du changement

- GitHub, l'une des plus grandes plateformes d'hébergement de code, a officiellement adopté "main" comme nom par défaut pour la branche principale dans les nouveaux dépôts en octobre 2020.

- D'autres services et outils liés à Git ont également suivi cette initiative, faisant de "main" la nouvelle convention de nommage standard pour la branche principale dans les nouveaux projets.

4. Pratique actuelle

- Aujourd'hui, "main" est couramment utilisé comme la branche principale par défaut, bien que certains projets plus anciens puissent encore utiliser "master". Les utilisateurs peuvent renommer la branche principale dans leurs dépôts existants s'ils le souhaitent.
