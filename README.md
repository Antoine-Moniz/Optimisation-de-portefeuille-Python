# Optimisation-de-portefeuille-Python



Optimisation de Portefeuille avec Python
Ce projet explore des approches d'optimisation de portefeuilles financiers en utilisant diverses métriques de performance telles que le ratio de Sharpe, le ratio de Sortino et le ratio de Calmar. L'objectif est de développer des algorithmes robustes pour maximiser le rendement ajusté au risque tout en respectant les contraintes sur les poids des actifs.

Fonctionnalités
Calculs de performance : Implémentation des métriques de Sharpe, Sortino, et Calmar.
Optimisation des poids : Algorithmes utilisant scipy.optimize pour ajuster les poids des actifs.
Techniques avancées :
Contraintes sur les poids, incluant la gestion des positions vendeuses.
Algorithme d'évolution différentielle pour une optimisation robuste.
Intégration : Analyse des performances avec pyfolio et quantstats.
Structure des fichiers
fonctions.py : Contient toutes les fonctions principales pour le calcul des ratios, l'optimisation des poids et la gestion des contraintes.
pythonL3.ipynb : Un notebook Jupyter démontrant l'utilisation des fonctions dans des scénarios d'optimisation réels.
