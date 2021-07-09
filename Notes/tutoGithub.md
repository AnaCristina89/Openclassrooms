# Git et github

## Initialiser un dépôt en vous basant sur l’exemple “PremierProjet”.
* git init 
Indexez vos fichiers avec la commande git add
* git add files.ext
Créez une nouvelle version avec la commande git commit
* git commit -m “jolie message"

## Envoyez votre commit sur le dépôt distant avec la commande git push
* git remote add origin urlRepository

Depuis le 1er octobre 2020, tous les nouveaux dépôts créés sur GitHub sont appelés “main”, au lieu de “master” comme c’était le cas historiquement. 
* git branch -M main
* git push -u origin main

## Créer une version du projet avec le fichier HTML à jour et l’envoyer sur le dépôt distant GitHub

* git add index.html
* git commit -m “Modification du titre H1”
* git push origin main

