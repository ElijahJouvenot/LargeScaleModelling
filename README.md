# LargeScaleModelling
## Description
Ce projet, réalisé dans le cadre du cours "Large-Scale Models and Simulation Methods" (Printemps 2024), vise à simuler le transport dans une ville française en utilisant une approche basée sur les agents. Bien que l'objectif de cette simulation ne soit pas de fournir des résultats exacts, elle sert à démontrer l'application des outils de simulation et des méthodes d'analyse sur les données de transport.

## Objectifs
Le projet se compose de plusieurs exercices couvrant différents aspects de l'analyse et de la modélisation des flux de transport :
  - Analyse territoriale : identifier et caractériser la zone d'étude (municipalité et voisines).
  - Production et attraction de déplacements : modéliser le nombre de trajets générés et attirés par chaque municipalité.
  - Distribution des trajets : calculer la matrice de flux de déplacements entre les zones.
  - Désagrégation et routage : simuler des trajets individuels et calculer les routes empruntées à partir des données OpenStreetMap.
    
## Librairies
Ce projet utilise plusieurs bibliothèques essentielles pour l’analyse, la visualisation et la simulation des données de transport :
  - **Pandas** : pour le traitement et la manipulation des données en tables, facilitant le filtrage et l’analyse des statistiques démographiques et socio-économiques.
  - **Geopandas** : pour manipuler des données géographiques et réaliser des analyses spatiales sur les zones d'étude, permettant de visualiser les municipalités sur une carte.
  - **NumPy**: pour les calculs numériques complexes, incluant les opérations sur les matrices de flux et le traitement des données de population.
  - **Matplotlib** et Plotly Express : pour créer des visualisations statiques et interactives, permettant de mieux comprendre la distribution et les flux de déplacement.
  - **Shapely** : pour manipuler les objets géométriques, notamment les polygones des zones de simulation, nécessaires pour les analyses géospatiales.
  - **OSMnx** : pour télécharger et traiter les données routières d'OpenStreetMap, essentiel pour modéliser et visualiser les trajets sur le réseau routier.
  - **NetworkX** : pour la création et la manipulation de graphes, utilisé ici pour modéliser le réseau de routes et effectuer les calculs de routage entre les zones d’origine et de destination.
