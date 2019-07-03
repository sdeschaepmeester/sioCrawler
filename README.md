# sioCrawler
sio crawler
>Présentation du projet: le but est de réaliser un jeu de rôle permettant un jeu
peu massivement multi joueur permettant aux étudiants du bts sio de se divertir pendant 
les heures de cantine mais surtout d'améliorer leurs compétences en développement.
>
Les outils mis en oeuvre :
>
*git
>
*visual studio
>
*mysql
>
*apache
>
Le développement tourne autour de 3 grandes parties
>
1.L'inscription en ligne
>
2.Développement du jeu en lui même permettant l'exploration d'un labyrinthe
>
3.La sauvegarde des personnages et du contexte du jeu
>
|développement         |langages |techniques de programmation                   |
|----------------------|:-------:|:--------------------------------------------:|
|inscription en ligne  |php,Mysql|développement web MCV avec code igniter       |
|sio crawler le jeu    |c#       |programmation objet, tests unitaires          |
|sauvegarde du contexte|c#, mysql|programmation procédurale, stockées en mysql  |
>
# L'inscription en ligne.
>
site web permettant à un joueur de s'inscrire en ligne.Le projet prévoit le principe suivant 
pour l'inscription en ligne.
![acteurFluxInscription.png](imagesTpGit/acteurFluxInscription.png)
![image](http://zupimages.net/viewer.php?id=19/27/3i31.png)
>
# sio crawler le jeu
>
Le joueur possèdera les fonctionnalités suivantes:
![useCasePersonnage.png](imagesTpGit/useCasePersonnage.png)
les classes développées
![diagrammeClassePersonnage.png](imagesTpGit/diagrammeClassePersonnage.png)
>
# Sauvegarde du contexte
>
La sauvegarde du contexte se fera dans la base de données.
![mcdSauvegarde.png](imagesTpGit/mcdSauvegarde.png)
