# Projet Phaser – Description

## Présentation du projet
Ce projet utilise le framework Phaser 3 pour créer une scène animée composée d’une grille de blocs visuels. L’objectif est de générer un effet visuel dynamique rappelant une vague ou une respiration, grâce à l’utilisation des tweens de Phaser.

## Fonctionnalités principales
- **Chargement d’assets** : une image de fond et un sprite carré de 50x50 pixels.
- **Création d’un groupe d’objets** : génération automatique de 108 blocs mis à l’échelle.
- **Alignement en grille** : placement précis des blocs selon une grille de 12 colonnes et 9 lignes.
- **Animation séquentielle** : chaque bloc change d’échelle de façon répétée, avec un léger décalage temporel créant un effet d’onde.

## Comportement visuel
Les blocs s’animent de manière synchronisée par ligne : chaque ligne commence son animation après la précédente, produisant un mouvement fluide et hypnotique.  
L’effet repose sur des tweens configurés avec :
- une durée courte (300 ms),
- une animation en aller-retour (yoyo),
- un délai progressif qui se réinitialise à chaque nouvelle ligne.

## Améliorations possibles
- Modifier l’effet de vague (diagonale, circulaire, aléatoire).
- Changer la forme ou la couleur des éléments.
- Ajouter des interactions utilisateur (clic, survol, mouvement souris).
- Intégrer des particules ou des effets sonores.

