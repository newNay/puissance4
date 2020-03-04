# puissance4

***pour jouer au jeu, lancer Menu.py***

#### cliquer sur une colonne pour y jouer un coup, cliquer à nouveau pour faire jouer l'ia ####

l'ia est écrite dans le fichier minimax.pyx, nous avons utilisé un minimax à elaguage alpha beta
(une variable DIFFICULTY au début du ficher, permet de régler la profondeur du minimax)

pour la rendre plus performente, nous avons stocké les positions des joueurs dans des entiers, (bitmaps) qui sont "positions" et "mask" (les tests de puissance 4 sont fait par opérations bit à bit, dans la fonction alignements2(long bitmap)

le menu et la gestion des différentes fenêtres (arcade.View) sont écrits dans Menu.py

l'affichage du jeu (grille, pions, images) est géré dans MyGame.py, 
pour jouer un coup il suffit d'appeler la fonction play(colonne) de l'un des objets Player (humain ou ia)

*la vidéo: https://youtu.be/iMPfmCuNRZw*
