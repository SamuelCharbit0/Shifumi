Shifumi - Jeu Pierre Feuille Ciseaux

Contexte du projet :

Ce projet consiste à créer un petit jeu de Shifumi (pierre, feuille, ciseaux) en JavaScript.

Le but était de coder un jeu simple où :

- le joueur choisit entre pierre, feuille ou ciseaux
- l’ordinateur fait un choix aléatoire
- les choix sont comparés pour savoir qui gagne
- un score est calculé

la partie dure 10 manches.

Ce projet permet de pratiquer la manipulation du DOM, la logique de jeu et les événements JavaScript.

Fonctionnement du jeu :

- L’utilisateur clique sur une des trois images pour choisir son action.
- Il appuie sur le bouton “Jouer”.
- L’ordinateur choisit automatiquement une action au hasard.
- Le jeu affiche :
  - le choix du joueur
  - le choix de l’ordinateur
  - le résultat de la manche
  - le score
  - et la manche actuelle.
- Au bout de 10 manches, une fenêtre affiche le score final.

Implémentation technique :

1) HTML

Le fichier index.html contient :

- le titre du jeu
- une zone qui affiche les résultats (score, choix, manche)
- un bouton “Jouer”
- les trois images (pierre, feuille, ciseaux) avec un attribut data-choice

2) CSS

Le fichier style.css gère l’apparence :

- un fond en dégradé
- un cadre central pour le jeu
- des images interactives (effet hover et sélection)
- un bouton stylisé

L’objectif est d’avoir une interface simple, propre et visuelle.

3) JavaScript

Le fichier script.js contient toute la logique du jeu :

- récupération des éléments HTML
- gestion de la sélection du joueur
- choix aléatoire de l’ordinateur
- comparaison des choix
- mise à jour du score
- comptage des manches
- remise à zéro après 10 manches

Structure du projet :

/

|-- index.html

|-- style.css

|-- script.js

|-- assets

    |-- leaf.png
    
    |-- scissors.png
    
    |-- stone.png
