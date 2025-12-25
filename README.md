# Optimisation par descente de gradient – Implémentations et analyse

Ce dépôt contient une implémentation et une étude comparative de plusieurs algorithmes de descente de gradient issus des méthodes numériques d’optimisation.
L’objectif est de mettre en évidence l’importance de chaque méthode et le gain apporté par rapport à la descente de gradient classique, à travers des expérimentations concrètes.

Algorithmes implémentés

Les algorithmes suivants sont implémentés et analysés dans le notebook :

### Descente de gradient classique
Méthode de base reposant sur un pas fixe. Elle sert de référence pour l’analyse des performances et de la convergence.

### Descente de gradient à pas optimal
Variante où le pas est déterminé à chaque itération par une optimisation unidimensionnelle, permettant une convergence plus rapide et plus stable.

### Descente de gradient conjugué linéaire
Méthode particulièrement efficace pour les problèmes quadratiques. Les directions de descente sont conjuguées, ce qui permet une convergence en un nombre fini d’itérations.

### Descente de gradient conjugué non linéaire
Extension du gradient conjugué à des fonctions générales, combinant mémoire des directions précédentes et recherche de pas optimal.

## Contenu du projet

Le notebook DescenteDeGradient.ipynb contient :

L’implémentation détaillée de chaque algorithme

Le calcul et l’affichage de la valeur de la fonction objectif à chaque itération

Une visualisation graphique de la convergence

L’affichage du nombre d’itérations nécessaires pour chaque méthode

Une analyse qualitative du comportement des algorithmes

## Objectifs pédagogiques

Ce projet a pour but de :

Comprendre les limites de la descente de gradient classique

Montrer comment l’optimisation du pas ou de la direction améliore la convergence

Illustrer des concepts clés des méthodes numériques et de l’optimisation convexe

Faire le lien entre la théorie et des implémentations concrètes

## Technologies utilisées

Python 3

NumPy

Matplotlib

Jupyter Notebook

Lien avec SciPy

Les algorithmes implémentés dans ce projet sont également disponibles dans la bibliothèque SciPy, notamment via scipy.optimize, qui fournit des implémentations optimisées et largement utilisées en pratique.

## Exécution du notebook

Cloner le dépôt

Installer les dépendances nécessaires

Lancer Jupyter Notebook

Ouvrir et exécuter DescenteDeGradient.ipynb

Auteur

Projet réalisé dans le cadre de l’étude des méthodes numériques et de l’optimisation (niveau Master).
