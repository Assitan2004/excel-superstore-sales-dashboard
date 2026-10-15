# Tableau de bord des ventes et de la rentabilité (Excel)

## Présentation du projet
Ce projet présente un tableau de bord interactif développé sous Microsoft Excel à partir du jeu de données *Superstore* (plus de 9 900 lignes de transactions). L'objectif est d'analyser la performance commerciale de l'entreprise et d'identifier les axes d'amélioration en matière de rentabilité.

## Indicateurs clés de performance (KPI)
* **Chiffre d'Affaires Total (Sales) :** 2 295 273,92 $
* **Bénéfice Total (Profit) :** 285 988,28 $
* **Marge bénéficiaire globale :** 12,46 %
* **Volume total des commandes :** 5 009 transactions

## Outils et méthodes utilisés
* **Logiciel :** Microsoft Excel (fonctions avancées, agrégations).
* **Modélisation :** Tableaux Croisés Dynamiques (TCD) multi-axes.
* **DataViz :** Graphiques croisés dynamiques (histogrammes et barres).
* **Interactivité :** Segments (*slicers*) connectés pour filtrer dynamiquement les données.

## Principaux enseignements métier
* **Performance géographique :** La région *West* affiche la meilleure dynamique commerciale (725,4 k$ de CA avec une marge de 14,94 %). À l'inverse, la région *Central* présente une rentabilité plus faible.
* **Analyse par catégorie :** La catégorie *Technology* est la plus rentable (17,39 % de marge). La catégorie *Furniture* génère un chiffre d'affaires élevé (741,9 k$) mais une marge critique de 2,49 %, soulignant un problème de gestion des remises.
* **Zones déficitaires :** Des États comme le Texas et l'Ohio affichent des pertes nettes en raison de politiques de réductions excessives.

## Structure du dépôt
* `/data/` : Contient le jeu de données d'origine (provenance Kaggle).
* `/output/` : Contient le fichier Excel finalisé du tableau de bord (`Sample - Superstore-avec-graphes.xlsx`).
