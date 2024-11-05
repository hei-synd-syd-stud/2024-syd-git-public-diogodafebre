# Answers of Diogo Febre Diogodafebre

## Basics
### Task 1
On y trouve le fichier .git qui stocke l'historique des modifications, les configurations, et gère les branches, les fusions et les conflits.
Il permet de suivre les versions et de collaborer avec d’autres en synchronisant le projet avec des référentiels distants comme GitHub.
Le fichier svg ce trouvant dans img sert à visualisé les branches git du projet.
### Task 2
Un fichier untraked files est apparue. GIT à donc détecté qu'il y avait un fichier qui à été ajouter mais pas commité, ni suvie (les modifications ne sont pas tracées).
### Task 3
Le fichier Readme.md à été stage. Il n'y a donc plus de file untraked.
### Task 4
Le fichier README.md est redevenu unstage. Cela indique le fichier à été modifié
### Task 5
La première ligne de l'état d'un dépôt Git montre l'identifiant unique du dernier commit actif, appelé un hash, suivi des informations sur la branche actuelle, comme HEAD (qui pointe vers le commit en cours) et main (la branche principale).
Après les parenthèses, on peut voir des indications sur l'écart entre la branche locale et la branche distante, par exemple "ahead by X commits" si la branche locale a plus de commits, ou "behind by X commits" si elle en a moins, ainsi que l'état général du répertoire de travail, qu'il soit propre ou contenant des changements non validés.
### Task 6
Lorsque nous sommes revenus sur le commit "Initial commit", Git a restauré l'état du projet tel qu'il était à ce moment-là, supprimant temporairement tous les fichiers, dossiers ou modifications ajoutés après ce commit.
Seuls les éléments présents dans le projet lors de ce premier commit étaient visibles.
Quand nous sommes ensuite revenus au dernier commit, Git a rétabli le répertoire de travail dans son état le plus récent, incluant tous les fichiers, dossiers et modifications effectués depuis le commit initial, ramenant ainsi le projet à sa version finale.
## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)