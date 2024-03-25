# Projet B3RPI
Git du projet de 3ème année du Bachelor RPI.

Ce git contient le document oficiel de notre projet d'année.

 La rédaction du dernier se fait sur l'outil de préfèrence, après elle est collé dans dans VSCode dans sa branch et ensuite push sur git pour que le reste de l'équipe soit au courrant.
**Écrit en markdown**.

[Cliquez ici pour un rappel de la syntaxe md](https://docs.framasoft.org/fr/grav/markdown.html) !

## Collaborateurs
- Jules BLOC
- Matias DE WINNE
- Pamela PARDO

## Structure du repo
Ce repo contient une branch ***main*** pour le document principal, et 3 branches secondaires pour chacun des collaborateurs: ***jules***, ***matias*** et ***pamela***.

## Utilisation
- Personne travaille directement sur la banch ***main***.
- Dans leur branch, chaque utilisateur travaille sur la tâche qui lui a été assignée dans les ***Épics*** sur ***Notion***.
- Quand le travail est fini, l'utilisateur commit et push sur sa branch ( et met à jour l'état d'avancement de la tâche sur ***Notion*** ).
-  Pour pouvoir merger un commit avec le projet ***main***, il doit être validé en avance par les autres deux collegues. S'il n'y a pas de validation, l'utilisateur retravaille sa tâche, commit et push sur sa branch et le processus se répète.

## Rappel des commandes
- `git checkout -b nomDeLaBranche` = Changer de branch.
- `git branch` = Savoir dans quel branch on se trouve.
- `git add .` = Ajoute tous les changements faits dans la branch pour le commit. Le `.` designe le dossier dans lequel on se trouve.
- `git commit -m '1.1 Titre de la tâche : j'ai fait cela'`= Commit les changements, les sauvegarde. Assigne un titre au commit. Pour être plus descriptifs, le titre du commit doit être le titre de l'Épic et une description courte de ce qu'a été fait.
- `git push origin nomDeLaBranche` = Upload sur git les changements.
- `git pull origin nomDeLaBranche`= Télécharge les changements faits par les autres.

## Ordre de commandes
- Toujours faire un pull du **main**. Après, aller dans sa branch.
- Travailler dans sa branch.
- Toujours add, commit et push dans sa branch après le travail.
*Le nombre de commits ou de push n'est pas important*
