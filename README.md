**Introduction**
Ce projet vise à développer un modèle de machine learning capable de prédire avec précision le prix de vente de maisons à partir d'un ensemble de données provenant de la compétition Kaggle "House Prices: Advanced Regression Techniques".

**Objectifs**
Comprendre les facteurs influençant les prix de l'immobilier.
Construire un modèle de prédiction robuste et performant.
Évaluer la qualité des prédictions à l'aide de métriques appropriées.
**Données**
Source: Compétition Kaggle "House Prices: Advanced Regression Techniques"
Contenu: Un ensemble de données comprenant de nombreuses caractéristiques de maisons (superficie, nombre de chambres, année de construction, etc.) ainsi que leur prix de vente.
Nettoyage: Gestion des valeurs manquantes, des outliers et des données incohérentes.
Transformation: Encodage des variables catégorielles, normalisation des données numériques.
Création de nouvelles caractéristiques: Ingénierie des caractéristiques pour capturer des informations supplémentaires (par exemple, âge de la maison, interaction entre variables).
**Méthodologie**
Exploration des données:
Analyse descriptive : statistiques descriptives, visualisations (histogrammes, boîtes à moustaches, corrélogrammes).
Analyse exploratoire : identification des relations entre les variables, des caractéristiques importantes.
Modélisation:
Sélection des modèles: Choix de différents algorithmes de régression (régression linéaire, forêts aléatoires, XGBoost, etc.).
Entraînement: Entraînement des modèles sur les données d'entraînement.
Validation: Évaluation des modèles sur un jeu de données de validation pour ajuster les hyperparamètres.
Évaluation:
Métriques: Calcul du RMSE pour évaluer la performance des modèles.
Comparaison: Comparaison des performances des différents modèles pour sélectionner le meilleur.
**Résultats**
Performance: Le modèle a obtenu un score RMSE de 0,13795 sur le jeu de test.
Analyse des erreurs: Analyse des résidus pour identifier les sources d'erreur et les cas où le modèle est moins performant.
**Technologies utilisées**
Langage: Python
Bibliothèques: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Environnement: Jupyter Notebook, Google Colab
**Code**
Le code source du projet est disponible dans le répertoire [chemin vers le code].
