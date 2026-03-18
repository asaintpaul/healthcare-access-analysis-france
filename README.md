# Analyse de l'Accès aux Soins en France (Projet OUTINFO)

## Présentation
Ce projet vise à évaluer la qualité du maillage sanitaire français en combinant des données géographiques, démographiques et hospitalières. L'objectif est de dépasser les indicateurs simples pour proposer un **Index Global d'Accès** multicritères.

## Méthodologie
Nous avons suivi la chaîne de traitement de données complète :
1. **Fetch** : Récupération automatisée via APIs (Ameli, DREES, OSM).
2. **Clean & Structure** : Normalisation des codes INSEE et reprojection géographique (Mercator vers GPS).
3. **Model** : Création d'un score normalisé (0-100) basé sur 4 indicateurs clés.
4. **Analyze** : Statistiques descriptives et matrices de corrélation de Pearson.
5. **Visualize** : Cartographie interactive (Folium) et analyse de la distribution.

## Technologies Utilisées
* **Python** (Pandas, NumPy, Seaborn)
* **Géospatial** : Folium (Heatmaps, MarkerClusters)
* **Open Data** : Données de santé (SNDS), Démographie médicale (Ameli)

## Auteurs
* Andréa SAINT PAUL
* Guillemette CIPRIANO
