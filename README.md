# Analyse du Marché Immobilier Français (2021-2022-2025)
Problèmatique : Les prix immobiliers à Paris sont-ils significativement plus élevés que dans le reste de la France?


## Introduction
Ce projet a pour objectif d'analyser le marché immobilier français en utilisant des données de Demandes de Valeurs Foncières (DVF). L'étude se concentre sur la compréhension des tendances de prix, l'identification des zones les plus actives, et une comparaison détaillée des prix immobiliers entre Paris et le reste de la France pour l'année 2022.

## Données
Les données utilisées proviennent de fichiers DVF (Valeurs Foncières) réels, notamment :
- `ValeursFoncieres-2021.txt` : Données de transactions immobilières pour 2021 (France entière).
- `ValeursFoncieres-2025.txt` : Données de transactions immobilières pour 2025 (France entière - *à des fins de simulation de tendances*).
- `dvf-75.csv` : Données de transactions immobilières spécifiques au département de Paris (75).
- `dvf-2022.parquet` : Données de transactions immobilières pour 2022 (France entière).

Les jeux de données bruts sont prétraités pour inclure la conversion des dates, le nettoyage des valeurs manquantes et aberrantes, et la création de caractéristiques dérivées comme le `Prix_m2` (prix au mètre carré).

## Structure de l'Analyse
Le notebook est organisé en plusieurs sections clés :

1.  **Préparation et Exploration des Données (Simulées)** : Une introduction aux étapes de base avec un petit jeu de données simulé.
2.  **Analyse du Marché Immobilier Français (Données Réelles 2021-2025)** : Chargement et prétraitement des données DVF réelles pour la France entière (2021 et 2025).
3.  **Analyse Détaillée du Marché Français (2021-2025)** : Exploration des distributions de prix par type de bien, évolution annuelle et mensuelle, et identification des communes les plus actives.
4.  **Analyse Spécifique du Marché Parisien (75)** : Étude approfondie du marché immobilier à Paris, incluant la distribution des prix, les tendances temporelles et les arrondissements les plus chers.
5.  **Comparaison Paris vs Reste de la France (2022)** : Une analyse comparative des prix au mètre carré entre Paris et le reste de la France pour l'année 2022.

## Résultats Clés
- Les prix immobiliers à Paris sont significativement plus élevés que dans le reste de la France.
- L'analyse des données DVF révèle des tendances et des disparités importantes selon les types de biens et les régions.
- Des visualisations (histogrammes, boxplots, graphiques linéaires) illustrent les distributions de prix, les évolutions temporelles et les comparaisons régionales.
