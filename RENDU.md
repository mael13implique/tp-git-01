```markdown
# Rendu : mael13implique


- Dépôt : tp-git-01
- Site GitHub Pages : https://github.com/mael13implique/tp-git-01


## Ex2
git log --oneline :

217a6be (HEAD -> main, origin/main) ex2: corrige une faute
48728d0 ex2: ajout de trois lignes
5243860 ex2: crée les notes
d1c3123 ex1: initialise le dépôt


## Ex3
- config.local est-il encore dans l'historique ? Pourquoi ?

Oui il apparaît puisqu'il y rentré, ignorer le fichier ne revient pas à ignorer les traces de son apparition temporaire dans le staging.

## Ex4
- git status après avoir retiré brouillon.txt du staging :

On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	deleted:    brouillon.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   RENDU.md
	deleted:    ancien.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	brouillon.txt


- Différence entre annuler une modification et retirer du staging ?

Annuler une modification revient à l'état "initial", tandis que la retirer du staging transforme l'état actuel (après modification) en état initial.

Annuler une modification n'apparaît pas dans l'historique sans commit


## Ex6
- À quoi servent <<<<<<<, ======= et >>>>>>> ?

A signaler respectivement le début, le contenu et la fin de la partie du doc causant un conflit lors du merge.

## Ex7
- git stash list (avant récupération) : 

stash@{0}: WIP on main: f487fa9 ex7: ajoute une ligne par erreur

- Pourquoi annuler un commit plutôt que l'effacer de l'historique ?

Permet de garder une trace de la modification malgré son annulation (i.e garder une trace de toutes les opérations)

## Ex8
- git pull = git fetch + git merge

## Ex10
git log --oneline --graph --all :

https://mael13implique.github.io/tp-git-01/

```
