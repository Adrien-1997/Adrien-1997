# Adrien Morel — Data Scientist / Applied ML

Je conçois des **outils d’aide à la décision** à partir de données opérationnelles. Mon approche : cadrage métier clair → préparation de données rigoureuse → modèles lisibles et mesurés → **mise en production progressive** (qualité, CI/CD, monitoring).

- Paris (ou remote) — Ouvert à des opportunités Data Scientist / ML (CDI ou mission)  
- Contact : adrien.morel@gmail.com — LinkedIn : https://www.linkedin.com/in/adrien-morel/ — GitHub : https://github.com/Adrien-1997

---

## Compétences Data Science (Top)

### 1) Math/Stats appliquées
- Probabilités, statistiques inférentielles, **tests d’hypothèses**, intervalles de confiance  
- **Régression linéaire/logistique**, régularisation (L1/L2/ElasticNet), GLM  
- **Échantillonnage / re-échantillonnage** (bootstrap), **A/B testing**, puissance statistique

### 2) Préparation & Feature Engineering
- Qualité de données (valeurs manquantes, outliers, fusions, encodages catégoriels dont **target encoding**)
- Normalisation/standardisation, binning, **features temporelles** (lags, rolling, tendances), géo-features simples
- Text preprocessing (tokenisation, lemmatisation, n-grams), pipelines reproductibles

### 3) Modélisation supervisée
- **Arbres & ensembles** : Random Forest, **LightGBM/XGBoost**  
- Linéaires/GLM, SVM, k-NN ; gestion du **déséquilibre** (class weights, sampling)  
- Calibration, interprétabilité basique (permutation importance, SHAP light)

### 4) Non supervisé & Anomalies
- **Clustering** (k-means, DBSCAN/HDBSCAN), **réduction dimensionnelle** (PCA, t-SNE/UMAP)  
- **Détection d’anomalies** (IsolationForest, LOF, stats robustes)

### 5) Séries temporelles & Forecast
- Découpage saisonnier/tendance, **validation temporelle** (TimeSeriesSplit)
- Modèles classiques (ARIMA, VAR/GARCH) et **régressions sur lags/exogènes** (boosting)
- Métriques : **MAE/RMSE/MAPE**, coverage (PI)

### 6) NLP (appliqué)
- Représentations : **TF-IDF**, embeddings (word2vec/fastText) ; classification texte, **NER** simple  
- Métriques : **F1**, ROC-AUC, PR-AUC ; gestion du bruit / non-équilibré

### 7) Évaluation & Validation
- **CV** k-fold/stratifiée et **TimeSeriesSplit**, jeux de validation gelés
- Suivi des métriques métier (précision opérationnelle, coûts d’erreur, SLA)
- Courbes et diagnostics : résidus, **courbes d’apprentissage**, courbes de calibration

### 8) MLOps & Production
- Versionnement données/modèles (**Parquet, DuckDB, joblib**), reproductibilité (seeds, env)
- **CI/CD GitHub Actions**, packaging léger, déploiement batch/cron
- **Monitoring** : **drift** (PSI/KS), perf online (MAE/RMSE glissants), **politiques de retrain**

### 9) Data Engineering (essentiels)
- **SQL** avancé (joins, fenêtres), schémas propres, **ETL/ELT** incrémental
- Fichiers **Parquet**, **DuckDB** pour analytics locales, API REST
- Idempotence, logs, tests de non-régression sur jeux de données

### 10) Visualisation & Communication
- **Streamlit**, Power BI, notebooks clairs ; **storytelling** orienté décision
- KPI et tableaux de bord **actionnables** (lisibles pour non-techniques)
- Documentation technique **MkDocs** (guide d’usage, métriques, modèles)

---

## Stack technique
- **Python** : Pandas, NumPy, scikit-learn, **LightGBM**, TensorFlow/Keras (bases)
- **Data** : SQL, **DuckDB**, Parquet, Snowflake
- **Apps/Viz** : Streamlit, Power BI, Folium, **MkDocs (Material)**
- **Dev/MLOps** : Git, **GitHub Actions**, Docker (bases), joblib, pyarrow
- **Cloud** : Google Cloud (montée en compétence en cours)

---

## Formation & langues
- Ingénieur en **Mathématiques Appliquées** (CY Tech) ; Master **HPC**  
- Français (natif), **Anglais (C1)**, Espagnol (B2), Italien (B2)

---

## Méthode de travail
1. **Cadrage** avec métriques métier simples et observables  
2. **Prototype utile** rapide (data prep + modèle + évaluation claire)  
3. Itérations courtes guidées par l’usage  
4. **Montée en prod** : tests, CI/CD, monitoring & documentation

## Contact
Email : **adrien.morel@gmail.com** — LinkedIn : **https://www.linkedin.com/in/adrien-morel/** — GitHub : **https://github.com/Adrien-1997**
