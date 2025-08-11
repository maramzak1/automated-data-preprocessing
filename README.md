# 🚀 Automated Machine Learning Pipeline

## 📌 Description
Ce projet met en place un **pipeline automatisé** de machine learning en Python pour :
- Charger automatiquement les dernières données disponibles
- Prétraiter et nettoyer les données
- Détecter et supprimer les anomalies
- Entraîner et optimiser un modèle **LightGBM** avec **Optuna**
- Évaluer le modèle avec plusieurs métriques
- Sauvegarder le modèle et le scaler pour réutilisation

## 🛠 Technologies utilisées
- **Python 3**
- **Pandas / NumPy** – Manipulation et nettoyage des données
- **Category Encoders** – Encodage Leave-One-Out
- **Scikit-learn** – Prétraitement, détection d’anomalies, métriques
- **LightGBM** – Modélisation
- **Optuna** – Optimisation d’hyperparamètres
- **Joblib** – Sauvegarde du modèle

## 📂 Fonctionnalités du pipeline
1. **Chargement automatique** du fichier de données le plus récent
2. **Prétraitement des données**
   - Nettoyage et formatage
   - Encodage des variables catégorielles
   - Détection/suppression des anomalies (*Isolation Forest*)
   - Normalisation (*StandardScaler*)
3. **Validation croisée** avec *K-Fold*
4. **Optimisation des hyperparamètres** avec *Optuna*
5. **Entraînement et sauvegarde** du modèle LightGBM
6. **Évaluation** : MAE, RMSE, R²
7. **Exportation des résultats**

