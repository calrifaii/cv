# Projet : Jeu "Avoid the Germs"

## Description
Ce projet est un petit jeu d’arcade développé en **JavaScript** à l’aide du framework **Phaser 3**.  
Le joueur contrôle un personnage qui doit **éviter les germes** animés tout en **ramassant des anneaux** pour gagner des points.  
Le jeu se termine dès qu’un germe touche le joueur.

---

## Objectifs du projet
- Créer un jeu web interactif en utilisant **Phaser 3**
- Gérer des scènes de jeu (menu principal, chargement, gameplay)
- Apprendre la gestion des collisions, de la physique et des animations en JavaScript
- Concevoir un système de score et de “highscore”

---

## Fonctionnalités principales
- **Contrôle du joueur** : déplacement avec la souris  
- **Ennemis (germes)** : apparaissent et poursuivent le joueur avec des vitesses différentes  
- **Objets à collecter** : des anneaux à ramasser pour augmenter le score  
- **Sons et musiques** : effets audio pour les actions (victoire, échec, etc.)  
- **Interface dynamique** : menu principal, écran de “Game Over”, affichage du score  

---

## Technologies utilisées
- **Phaser 3** (moteur de jeu 2D en JavaScript)
- **HTML5 / CSS3**
- **JavaScript (ES6 modules)**
- **GitHub Pages** pour l’hébergement

---

## Structure du projet
- `Boot.js` : chargeur initial du jeu  
- `Preloader.js` : gestion du chargement des assets (images, sons, etc.)  
- `MainMenu.js` : menu principal et lancement du jeu  
- `MainGame.js` : logique principale du gameplay  
- `Player.js`, `Germ.js`, `Pickups.js`, `Germs.js` : gestion des objets du jeu  

---

## Résultat attendu
Un jeu d’arcade jouable directement dans le navigateur où :
- Le joueur doit survivre le plus longtemps possible,
- Éviter les germes en mouvement,
- Ramasser des anneaux pour battre le meilleur score.

Le jeu sera hébergé sur GitHub Pages et accessible via un simple lien.

---

## Auteur
**Chahnaz Alrifaii** — Étudiante en mastère Humanités Numériques.
