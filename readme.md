# Commandes git

liste des commandes git

## git init

- initialise un nouveau dépôt git

## git add

- permet d' ajouter les fichiers  ou des modifications dans le dépôt

## git commit
- permet d'enregistrer les modifications dans le dépôt en local
- le message est important pour les autres développeurs

## git push
- permet d'envoyer les modifications dans le dépôt en local vers le dépôt distant

## git status
. affiche les fichiers non commités
- permet de voir les fichiers non commités

## git log
- affiche les commits
- permet de voir les commits

## git branch
- permet de créer des branches

## git checkout
- permet de basculer entre les branches
- permet de se déplacer entre les branches
- avec l'option -b, permet de créer une nouvelle branche , et de se déplacer sur celle-ci , si elle n'existe pas encore

## git pull
permet de récupérer les modifications depuis le dépôt distant

## git rebase
- permet de récuperer les modifications depuis le dépôt distant et de les réappliquer sur le dépôt local 

- les modifications sont appliquées dans l'ordre où elles ont été réalisées( les modifications de la branche mere sont appliquées en dessous,  les modifications de la branche develop sont appliquées en premier)

- les modifcations de la branche courante sont appliquées en dessus des,  modifcation de la branche mere

