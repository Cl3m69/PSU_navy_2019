# PSU_navy_2019

Le but de ce projet est de réaliser un programme qui reconstitue le jeu de la bataille navale, avec un mode jouable entre deux terminaux grâce à l'utilisation des signaux.

Le joueur possède 4 bateaux de longueurs 2,3,4 et 5. Il les positionnes grâce à un fichier .txt dont les exemples sont donnés dans le dossier log.

Usage Joueur1 : $>./navy [pos.txt]
Usage Joueur2: $>./navy [PID Joueur1] [pos2.txt]

Usage avec un script joueur1: $>cat script | ./navy [pos.txt]
Usage avec un script joueur2: $>cat script | ./navy [PID joueur 1][pos2.txt]

Projet 100% a la moulinette
