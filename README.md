# README - Analyse des Campagnes Marketing et Réactivité des Clients

## Contexte

Ce projet vise à analyser la réactivité des clients face aux campagnes marketing en fonction de leurs caractéristiques spécifiques. L'objectif final est de développer un modèle de classification permettant de prédire la propension des clients à être intéressés par des offres publicitaires, optimisant ainsi les plans marketing et augmentant les taux de conversion.

## Objectifs

### Analyse Exploratoire des Données (EDA) : Comprendre la distribution des variables et leur impact sur la réactivité des clients.

### Modélisation : Construire un modèle de classification pour prédire les réponses des clients aux campagnes.

### Optimisation Marketing : Utiliser les insights pour cibler efficacement les clients et adapter les campagnes.

## Structure du Projet

### Notebooks : Contient les analyses exploratoires et les modèles.

notebook.ipynb : Analyse initiale des données et visualisations.

Data : Dossier contenant les jeux de données.

marketing_campaign.csv : Données des campagnes marketing.

### Bibliothèques Utilisées

numpy, pandas : Manipulation des données.

matplotlib, seaborn : Visualisation des données.

scikit-learn : Modélisation et évaluation.

### Données

Le jeu de données marketing_campaign.csv contient 2240 lignes et 29 colonnes, incluant des informations telles que :

Démographiques : Âge, éducation, statut marital, revenu.

Comportementales : Dépenses par catégorie de produits, visites web.

Réponses aux Campagnes : Acceptation des campagnes passées (AcceptedCmp1 à AcceptedCmp5).

Variable Cible : Response (réponse à la dernière campagne).

### Étapes Clés

1. Chargement et Nettoyage

Importation des données.

Gestion des valeurs manquantes et des doublons.

2. Analyse Exploratoire

Distribution des variables.

Corrélations entre les caractéristiques et la variable cible.

Visualisations pour identifier des tendances.

3. Préparation des Données

Encodage des variables catégorielles.

Normalisation des données numériques.

Séparation en ensembles d'entraînement et de test.

4. Modélisation

Entraînement de modèles de classification (Logistic Regression, Decision Trees, Random Forest).

Évaluation des performances (Précision, Rappel, AUC-ROC).

5. Interprétation

Importance des caractéristiques.

Recommandations pour les campagnes futures.

Résultats Attendus

Un modèle prédictif fiable pour identifier les clients réactifs.

Des insights actionnables pour optimiser les stratégies marketing.

Visualisations clés pour communiquer les résultats.


Installer les dépendances :

pip install numpy pandas matplotlib seaborn scikit-learn

Exécuter les notebooks :

Ouvrir notebook.ipynb pour l'analyse exploratoire.

Suivre les étapes pour entraîner et évaluer les modèles.

