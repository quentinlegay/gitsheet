Changer le remote d’un repo

``` bash 
git remote set-url origin <new_url>
``` 

Récupérer les changements de la branche master origin sur sa branche :

``` bash 
git checkout master
git pull
git checkout myBranch
git merge master
``` 

Supprimer une branche locale

``` bash 
git branch -d <nom_de_ma_branche>
``` 

Modifier le message du dernier commit avant un push

Pour modifier le message du dernier commit avant de pousser les modifications, utilise la commande suivante :

```bash
git commit --amend
```

Cela ouvrira l'éditeur de texte configuré pour Git, où tu pourras modifier le message du dernier commit. Après avoir modifié le message, enregistre et ferme l'éditeur.

Ensuite, tu peux pousser le commit amendé avec l'option --force (ou -f) pour forcer la mise à jour sur le dépôt distant :

```bash
git push --force
```

*_Attention_*

Utilise la commande --force avec précaution, surtout si tu travailles en collaboration avec d'autres développeurs, car cela réécrit l'historique Git et peut causer des problèmes si d'autres personnes ont déjà tiré les commits modifiés.