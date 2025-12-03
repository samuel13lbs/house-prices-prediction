# House Prices Prediction

Projet réalisé dans le cadre d'un exercice sur le dataset [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

L'objectif est de prédire le prix de vente des maisons à Ames, USA, en utilisant des variables structurelles, de localisation et de qualité.

---

## Contenu du projet

- `main.py` : script Python complet pour :
  - Préparer les données (imputation, encodage, log transformation)
  - Entraîner un modèle XGBoost
  - Effectuer une cross-validation (RMSE log)
  - Générer les prédictions sur le jeu test
- `predictions.csv` : résultats des prédictions sur le jeu test
- `.gitignore` : exclut les fichiers inutiles ou volumineux

> Les fichiers `train.csv` et `test.csv` ne sont pas inclus pour ne pas surcharger le dépôt.

---

## Installation

1. Cloner le dépôt :
```bash
git clone https://github.com/samuel13lbs/house-prices-prediction.git
cd house-prices-prediction

##Installer les dépendances :

pip install numpy pandas scikit-learn xgboost joblib
