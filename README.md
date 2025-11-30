🌍 Prédiction de la Qualité de l’Air — Projet Machine Learning

Ce projet a pour objectif de prédire la qualité de l’air à l’échelle mondiale en utilisant des techniques de Machine Learning.
Il s’appuie sur un dataset réel contenant des mesures de pollution provenant de plus de 23 000 villes dans le monde (2017–2022).

---
📦 Dataset

Source : Kaggle — Global Air Pollution Dataset (Hasib Al Muzdadid, 2022)
Lien : https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset

Contenu :

Polluants : CO, Ozone, NO2, PM2.5

Informations géographiques : pays, ville, latitude, longitude

Cible : AQI Value (indice 0–500) et AQI Category
---

🎯 Objectifs du Projet

Explorer et analyser les données

Visualiser la pollution à l’échelle mondiale

Préparer et nettoyer le dataset

Construire plusieurs modèles de classification :

Baseline

Régression Logistique

KNN

Arbre de Décision

Random Forest

SVM

Comparer les performances des modèles

Identifier les polluants les plus déterminants

Formuler des recommandations environnementales

🧪 Méthodologie
1. Exploration

Statistiques descriptives

Analyse des valeurs manquantes

Visualisations (histogrammes, boxplots, heatmaps)

2. Préparation des données

Nettoyage

Feature engineering

Transformation en classification binaire :

Bon air : AQI < 100

Mauvais air : AQI ≥ 100

Normalisation des variables

3. Modélisation

Entraînement et évaluation avec :

Accuracy

Precision / Recall / F1-score

AUC-ROC

Matrice de confusion

4. Optimisation

GridSearchCV

Validation croisée

Tableau comparatif des modèles

📊 Livrables

Notebook Jupyter complet

Visualisations commentées

Analyse et réponses aux questions

Rapport d’une page : recommandations environnementales

Export PDF du notebook

📝 Résultats Attendus

Code structuré, propre et commenté

Modèle atteignant > 75% d’accuracy sur le test set

Analyse pertinente du contexte environnemental

Interprétation des features et des erreurs

🧠 Ressources utiles

OMS – Qualité de l’air

EPA – AQI Basics

Documentation Scikit-learn

OpenAQ / WHO Air Quality Database
