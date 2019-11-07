# Morpion

### 1. initialisation des differents parametres:
		-la grille
		-une case de la grille
		-le scanner
		-et les joueurs
		
### 2. affichage de la grille.
		une boucle dans une boucle poyur afficher chaque case de la grille.
		
### 3. selection case de la grille.
		Temps que la boucle while est vrai je demande au joueur de selectionner une case,tente de transformer le string du scanner entré par l'utilisateur en numerique, si reussi passe à l'etape suivante, sinon renvoie une erreur.
		Verifie si la case de grille courante n'a pas deja ete utilisé et compris entre 0 et 8.
		
### 4. placer le jeton du joueur courant.
		Transforme le numero de la case en colonne et ligne,puis
		place le jeton du joueur courant sur la grille.
		
### 5. verifier si un joueur a gagné.
		retourne un booleen pour verifier qu'il y a un gagant et termin� le programme.
		fait les tests pour les colonnes, les lignes, et les diagonals.
		
### 6:. changer de joueur.
		je verifie si il y a un gagnant avant de changer de joueur.
		Puis j'echange les joueurs et affiche la grille.
		
		

		
### Dans ma fonction main je crée une instance du morpion, puis je teste si un gagnant pour finir le jeu. et je lance chaque methode l'une apres l'autre.
	