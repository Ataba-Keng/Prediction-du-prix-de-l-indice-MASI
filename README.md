# 📈 Prédiction du prix de l'indice boursier MASI

Étude de cas : **prédiction du prix de l'indice MASI** (Bourse de Casablanca) à partir de données historiques, approche **Random Forest** (régression) avec validation croisée.

---

## 🇫🇷 Français

### 🎯 Objectif
Anticiper l'évolution du **prix de l'indice MASI** (Marché des Actions et des Indices) à partir d'un historique de données financières (`Dataset.xlsx`).

### 🏗️ Démarche
1. **Import & exploration** — chargement Excel, compréhension des séries temporelles.
2. **Prétraitement** — nettoyage, transformations, préparation des features.
3. **Modélisation** — division entraînement/test, **Random Forest** (régression), optimisation.
4. **Évaluation** — **validation croisée (5 folds)**, MSE, RMSE et précision sur test.

### 🛠️ Technologies
Python · pandas · scikit-learn (Random Forest) · openpyxl · matplotlib / seaborn

### 📊 Résultats
- **R² ≈ 0,999** sur le test, **MSE ≈ 1791**, RMSE ≈ 42,3.
- **Validation croisée stable** : scores ≈ 0,998 sur les 5 folds (faible variance).
- ⚠️ Limite à connaître : les métriques R² sur série temporelle doivent être interprétées avec prudence (autocorrélation).

---

## 🇬🇧 English

### 🎯 Objective
Forecast the **MASI index price** (Casablanca Stock Exchange) from historical data, with a **Random Forest** regression approach and cross-validation.

### 🏗️ Approach
1. **Import & exploration** — Excel loading, understanding the time series.
2. **Preprocessing** — cleaning, transformations, feature preparation.
3. **Modelling** — train/test split, **Random Forest** regression, tuning.
4. **Evaluation** — **5-fold cross-validation**, MSE, RMSE and test accuracy.

### 🛠️ Tech Stack
Python · pandas · scikit-learn (Random Forest) · openpyxl · matplotlib / seaborn

### 📊 Results
- **R² ≈ 0.999** on the test set, **MSE ≈ 1791**, RMSE ≈ 42.3.
- **Stable cross-validation**: scores ≈ 0.998 across 5 folds (low variance).
- ⚠️ Caveat: R² on time-series must be interpreted carefully (autocorrelation).

---

### 📓 Démarrage / Quick start
Ouvrir `Etude_de_cas_ATABA_KENG.ipynb` (Jupyter) — données dans `Dataset.xlsx`.