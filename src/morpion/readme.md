Morpion

etape 1:initialisation des differents parametres.
		la grille
		une case de la grille
		le scanner
		et les joueurs
		
etape 2:affichage de la grille.
		une boucle dans une boucle poyur afficher chaque case de la grille.
		
etape 3:selection case de la grille.
		temps que la boucle while est vrai je demande au joueur de selectionner une case,
		tente de transformer le string du scanner entr� par l'utilisateur en numerique,
		si reussi passe � l'etape suivante, sinon renvoie une erreur.
		Verifie si la case de grille courante n'a pas deja ete utilis� et compris entre 0 et 8.
		
etape 4:placer le jeton du joueur courant.
		Transforme le numero de la case en colonne et ligne,puis
		place le jeton du joueur courant sur la grille.
		
etape 5:verifier si un joueur a gagné.
		retourne un booleen pour verifier qu'il y a un gagant et termin� le programme.
		fait les tests pour les colonnes, les lignes, et les diagonals.
		
etape 6:changer de joueur.
		je verifie si il y a un gagnant avant de changer de joueur.
		Puis j'echange les joueurs et affiche la grille.
		
		
Dans ma fonction main je cr�e une instance du morpion, puis je teste si un gagnant pour
finir le jeu. et je lance chaque methode l'une apres l'autre.
	