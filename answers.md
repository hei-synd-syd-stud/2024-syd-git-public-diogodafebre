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
1) develop : Nom de la branche de développement.
2) baa6795 : Hash du commit (identifiant unique) pour le commit "Merge branch 'feature-auth' into 'develop'".
3) Message de commit : "Merge branch 'feature-auth' into 'develop'" est le message associé à ce commit, indiquant une fusion de la branche feature-auth dans develop.
4) Auteur du commit : ByteMe Bob bob.byteme@hevs.ch est l’auteur du commit de fusion de la branche feature-auth dans develop.
5) v1.0.0 : Tag ou version indiquant la première version stable ou majeure du projet. Il est associé au commit 7725aa3.
6) Représente un commit sur la branche develop (en bleu) qui est aussi un point de fusion avec la branche feature-auth (en jaune). Ce commit intègre probablement des modifications de la branche feature-auth dans develop.
7) Correspond à un commit sur la branche feature-auth, où une fonctionnalité spécifique (comme l'authentification utilisateur) a été développée. Ce commit est ensuite fusionné dans la branche develop.
8) Ce point représente la branche main (en gris). Il est au même niveau que la fusion entre develop et feature-auth, indiquant une possible version stable prête pour la production, ou une version taguée.
9) Ce point fait partie de la branche main et correspond à un commit intermédiaire dans l'historique, montrant le développement progressif du projet.
10) Il s'agit du "commit initial" (initial commit) du projet, le tout premier commit dans la branche main, où le dépôt a été initialisé.


### Task 7

![Gitgraph](img/gitgraph.svg)