# 🛳 Titanic - Machine Learning from Disaster

Ce projet est une participation à la compétition Kaggle [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic). L'objectif est de prédire la survie des passagers à partir de caractéristiques telles que le sexe, l'âge, la classe sociale, etc.

# 📊 Étapes réalisées

📌 1. Importation et exploration des données
Visualisation des premières lignes

Observation des dimensions et types de variables

Analyse des valeurs manquantes

🧼 2. Nettoyage des données
Remplissage des valeurs manquantes (Age, Embarked)

Suppression des colonnes peu utiles (Cabin, Ticket)

Encodage des variables catégorielles (Sex, Embarked)

🛠 3. Feature Engineering
Création de nouvelles variables comme Title à partir du nom

Regroupement des passagers par classes sociales

🤖 4. Modélisation
Tu as testé plusieurs modèles :

Logistic Regression

Support Vector Machines (SVC)

K-Nearest Neighbors

Random Forest

Gaussian Naive Bayes

Perceptron

Stochastic Gradient Descent (SGD)

Decision Tree

✅ Le modèle le plus performant semble être RandomForestClassifier (à confirmer selon la cellule finale).