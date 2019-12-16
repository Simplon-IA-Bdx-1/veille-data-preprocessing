# veille-data-preprocessing

1) Pre-processing:
- Sklearn.impute
- Sklearn.preprocessing
2) Pipelines:
- Application pour enchaîner SimpleImputer, PCA et StandardScaler sur dataset de features numériques
- Application pour enchaîner SimpleImputer et OneHotEncoder sur dataset de features catégorielles
https://www.kaggle.com/lucabasa/understand-and-use-a-pipeline 

3) ColumnTransformer
pour préparer dataset contenant des features numériques et des features catégorielles
Enchaîner avec un classifier ou un regressor pour créer un modèle
