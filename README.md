# Projet B3RPI
Git du projet de 3ème année du Bachelor RPI.

Ce git contient le document oficiel de notre projet d'année.

 La rédaction du dernier se fait sur l'outil de préfèrence, après elle est collée dans le VSCode contenant ce repo, sur la bonne branch et ensuite, push sur git pour que le reste de l'équipe soit au courrant.

**Écrit en markdown**.

[Cliquez ici pour un rappel de la syntaxe md](https://docs.framasoft.org/fr/grav/markdown.html) !

## Collaborateurs
- Jules BLOC
- Matias DE WINNE
- Pamela PARDO

## Structure du repo
Ce repo contient une branch ***main*** pour le document principal et 3 branches secondaires pour chacun des collaborateurs: ***jules***, ***matias*** et ***pamela***.

## Utilisation
- On travaille sur VSCode
- Personne travaille directement sur la banch ***main***.
- Dans leur branch, chaque utilisateur travaille sur la tâche qui lui a été assignée dans les ***Épics*** sur ***Notion***.
- Quand le travail est fini, l'utilisateur add, commit et push sur sa branch ( et met à jour l'état d'avancement de la tâche sur ***Notion*** ).
-  Pour pouvoir merger un commit avec le projet ***main***, un **pull request** doit être crée et il doit être validé par les autres deux collegues. S'il n'y a pas de validation, l'utilisateur retravaille sa tâche, commit et push sur sa branch et le processus se répète.

## Processus de validation
 Dissons que votre commit a déjà été push dans votre branch et maintenant vous voudriez informer le reste de l'équipe que votre travail a été fait pour qu'ils le valident, cela s'appelle **pull request**. Cette option apparaît dans le site git du repo lorsque vous faites un push sur votre branch. Vous cliquez dessus, vous assignez de **reviewers**, vous écrivez un commentaire si pertinant et vous validez. Un pull request sera créé et votre équipe sera informé.

 Pour demander des changements, les **reviewers** doivent écrire un commentaire dans la ligne qui doit être modifé.

 Pour valider le travail, les deux **reviewers** doivent valider le commit. Dès qu'il est validé par tous, il faut alors clicker sur **Merge**. Cela mettra à jour le fichier **main** en ajoutant les nouveaux paragraphes validés.

## Rappel des commandes
- `git checkout -b matias` #Changer de branch.
- `git branch` #Savoir dans quel branch on se trouve.
- `git add .` #Ajoute tous les changements faits dans la branch pour le commit. Le `.` designe le dossier dans lequel on se trouve.
- `git commit -m '1.1 Titre de la tâche : j'ai fait cela'` #Commit les changements, les sauvegarde. Assigne un titre au commit. Pour être plus descriptifs, le titre du commit doit être le titre de l'Épic et une description courte de ce qu'a été fait.
- `git push origin matias` #Upload sur git les changements.
- `git pull origin main` #Télécharge les changements faits par les autres.

## Ordre de commandes
- Toujours faire un pull du **main**. Après, aller dans sa branch.
- Travailler dans sa branch.
- Toujours add, commit et push dans sa branch après le travail.
*Le nombre de commits ou de push n'est pas important*
