
![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)

# Commandes Git

#### Git init
> git init
> Initialized empty Git repository in /Users/nartawak/Workspaces/Formations/formation-module-git/src/TPs/01_Command/samples/first-repo/.git/

#### Git status
Permet de déterminer l'état de la commande.
> git status
> On branch master
> No commits yet
> ...

#### Git commit
Permet de valider les modifications effectuées.
>git commit

Il est possible d'utiliser l'option -m pour définir un message directement en ligne de commande.
>git commit -m "Ajout du fichier playground.txt"

##### Modifier le dernier commit
Cette opération **n'est pas sans conséquence** car elle modifie l'historique. Modifier un commit signifie que l'on va créer un nouveau commit.
>git commit -a --amend -m "Amend commit"
>
#### Git log
Permet de connaitre sur quel commit nous sommes positionnés.
>git log
>commit c8e8a6e663828c0753ba21e163237ab7bd4bf17b (HEAD -> master)
>Author: ARichaudeau <>
>Date: Mon Nov 12 14:20:27 2018 +0100

#### Git fetch
A toi d'ajouter la description
