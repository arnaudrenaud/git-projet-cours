# Git : pratique

## Commandes de base

### Initialiser un nouveau dépôt Git et créer un commit

Exécuter la commande `git init` à la racine du dossier contenant le projet. Ceci créera un dossier `.git` à la racine du projet.
Exécuter `git add .` puis `git commit -m 'Titre du commit'`.

### Visualiser l'historique

Exécuter `git log`. Vous verrez la liste des commits, du plus récent au plus ancien, en partant de la tête de lecture actuelle. Chaque commit contient le nom de l'auteur et la date d'enregistrement.

### Changement expérimentaux

Pour faire des changements expérimentaux, créer une nouvelle branche.

### Mettre de côté son travail

Exécuter `git stash` pour mettre le travail en cours de côté.
Exécuter `git stash pop` pour le remettre dans l'espace de travail.
Exécuter `git stash list` pour voir les différents ajouts.

## Pull requests

Sur GitHub, une pull request est un fil de discussion pour améliorer une branche avant de l'incorporer à la branche principale.
Une fois poussée, d'autres commits peuvent être ajoutés à la branche et apparaîtront dans la pull request.
Une fois la pull request close, on peut supprimer la branche associée.
