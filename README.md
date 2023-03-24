# aim_lab
Ce code est un jeu simple où le joueur doit toucher une cible en mouvement avec le curseur de sa souris. La cible est représentée par un ensemble de cercles de différentes couleurs, et elle se déplace horizontalement sur l'écran tout en oscillant verticalement. Le score du joueur est incrémenté chaque fois qu'il touche la cible. Le jeu a une limite de temps de 10 secondes, après quoi le score du joueur est affiché.

Le jeu commence avec un menu qui fournit des instructions au joueur. Pour commencer le jeu, le joueur doit appuyer sur la touche flèche HAUT. Pendant le jeu, le joueur peut appuyer sur la touche flèche GAUCHE pour réinitialiser le score et le temps.

Le code définit quelques classes :

Cible : représente l'objet cible et contient des méthodes pour afficher, déplacer et détecter les touches.
Demarrage : représente le menu et fournit des méthodes pour afficher le menu et arrêter le jeu.
Jeu : fournit des méthodes pour démarrer et réinitialiser le jeu, et pour incrémenter le score du joueur lorsqu'il touche la cible.
