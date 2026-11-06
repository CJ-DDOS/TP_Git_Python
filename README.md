TP Git / GitHub - Mon assistant de révision
Présentation
Ce projet contient un programme Python unique nommé main.py, réalisé dans le cadre des travaux pratiques d'outils collaboratifs (Licence 1). L'objectif est de concevoir un assistant de révision interactif tout en apprenant à versionner et synchroniser du code avec Git et GitHub.

Versions V1 à V4
Le même fichier main.py a évolué au travers de quatre versions successives :
V1 : Message initial de bienvenue, créé localement sur le PC.
V2 : Ajout du prénom de l'utilisateur, suivi du premier git push vers GitHub.
V3 : Ajout de la matière à réviser directement sur GitHub, puis récupération de la modification avec git pull.
V4 : Ajout de la durée de révision sur le PC, suivi d'un nouveau git push.

Comment exécuter le programme
Méthode 1 : Directement dans VS Code (Sans ligne de commande)
Ouvrez le dossier TP_Git_Python dans VS Code, puis cliquez sur le fichier main.py[span_5](start_span)[span_5](end_span).
Cliquez sur le bouton ▶ Run Python File situé en haut à droite de l'éditeur (choisissez l'interpréteur Python si demandé)[span_6](start_span)[span_6](end_span).
Dans le terminal intégré qui s'ouvre en bas, saisissez successivement votre prénom, la matière et la durée en minutes, en validant chaque réponse avec la touche Entrée[span_7](start_span)[span_7](end_span).

Méthode 2 : Via Git Bash
Ouvrez Git Bash dans le dossier du projet et tapez la commande suivante :
```bash
py main.py