# Prédiction des valeurs foncières en France  
### Projet de Master de Physique Appliquée – Université Paris Cité

## Description

Ce projet a été réalisé dans le cadre du Master 1 de Physique Appliquée à l’Université Paris Cité. Il vise à construire un modèle de prédiction des valeurs foncières à partir des données publiques DVF (Demandes de Valeurs Foncières), disponibles sur le portail [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/).

L'étude repose sur une chaîne de traitement de données incluant :
- Une analyse exploratoire,
- Une réduction de dimension par PCA,
- Un regroupement non supervisé (K-means),
- Des modèles de régression supervisée (régression linéaire, forêts aléatoires),
- Une analyse critique des performances et erreurs.

## Arborescence du projet

```
├── Projet.ipynb
├── data/
│ └── [fichiers DVF .csv à ajouter ici]
├── images/
├── deprecated/
└── README.md
```

## Données nécessaires

Le dossier `data/` **doit être rempli manuellement** avec les fichiers issus de la base "Demandes de valeurs foncières" accessible ici :

[https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/](https://www.data.gouv.fr/fr/datasets/5c4ae55a634f4117716d5656/)

Téléchargez les fichiers pour les années souhaitées (ex. 2019 à 2024) au format CSV et placez-les dans le dossier `data/` à la racine du projet.

## Environnement

Ce projet nécessite Python 3.7+ et les bibliothèques suivantes :

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

Projet réalisé dans le cadre du Master 1 Physique Appliquée
Université Paris Cité
