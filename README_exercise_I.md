# Car Price Predictor
Machine learning project to predict used car prices using the autocasion.csv dataset.

# Setup
1. Clone the repo: `git clone https://github.com/ASalonio/MLExercises.git`
2. Install dependencies: `pip install -r requirements_exercise_I.txt`
3. Run notebook: `jupyter notebook exercise_I.ipynb`

# Data and Model
- Dataset: [Download autocasion.csv](https://www.kaggle.com/datasets/augustosalonio/autocasion)
- Model: [Download best_model_exercise_I.pkl](https://www.kaggle.com/models/augustosalonio/best_model_exercise_i)

# Results
- Best model: XGBRegressor
- K-Fold CV (5 folds, Part III): R² ≈ 0.8758, MAE ≈ 2,000–5,000 € (estimated)
- Hold-Out (20% test set, Part II): R² ≈ 0.80–0.85 (estimated for RandomForest), with XGBRegressor showing robust generalization consistent with cross-validation.