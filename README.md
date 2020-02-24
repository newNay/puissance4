# puissance4

#### cliquer sur une colonne pour y jouer un coup, cliquer à nouveau pour faire jouer l'ia ####

l'ia est écrite dans le fichier minimax.pyx, nous avons utilisé un minimax à elagage alpha beta

le menu et la gestion des différentes fenêtres (arcade.View) sont écrits dans Menu.py

l'affichage du jeu (grille, pions, images) est géré dans MyGame.py, 
pour jouer un coup il suffit d'appeler la fonction play(colonne) de l'un des objets Player (humain ou ia)
