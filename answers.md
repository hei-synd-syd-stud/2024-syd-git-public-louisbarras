# Answers of Louis Barras LoulouBarras

## Basics

### Task 1

On retrouve les fichiers du projet tel que ce document text. Le dossier caché .git conserve les commandes git comme les commit, push.. 

### Task 2

git status : il y a un nouveau fichier README.md qui n'est pas enregistré (untracked file)

gi log --oneline : ne change pas 

### Task 3

Le fichier README.md a changé de status il est maintenant en "changes to be commited". il est en mode tracked file 

### Task 4

Le fichier README.md est modifié (état modified). il remarque qu'il y a eu des modifications

### Task 5

• Que signifie la chaîne de caractères au début ? identifiant unique du commit généré par notre ami Git
• Que signifient HEAD et main ? 

head : pointeur vers le commit, état actuel du dépot

main : le nom de la branche active
• Qu’est-ce qui se trouve après les parenthèses ?

message du commit, description des changements

### Task 6

checkout initial commit : les commit executés aprés sont temporairement cachés (dans une autre branch )

checkout main : le répertoire est mis a jour, le dernier changement est re ajouté au commit

## Gitgraph

### Task 7

1. nom de la branche , indiquée active
   
   2.  idantifiant unique du dernier commit abrégé
   
   3. description :  branch jaune merge avec branch bleu
   
   4.  auteur du commit
   
   5. desigantion de la version du main
   
   6. dernier commit réalisé
   
   7. commit réalisé par quelqu'un d'autre
   
   8. commit du main 
   
   9. tout les commit dans la branch develop 
   
   10. les commits sur la branch main

![Gitgraph](img/gitgraph.svg)