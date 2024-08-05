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