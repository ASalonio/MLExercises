# Fuel CO2 Emissions Predictor
Machine learning project to predict vehicle CO2 emissions using FuelConsumptionCo2.csv.

## Setup
1. Clone the repo: `git clone https://github.com/ASalonio/MLExercises.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebook: `jupyter notebook notebooks/exercise_II.ipynb`

## Data and Model
- Dataset: [Download fuel_consumption_co2_train.csv](https://www.kaggle.com/datasets/augustosalonio/fuel-consumption-co2-train)
- Model: [Download best_model_exercise_II.pkl](https://www.kaggle.com/models/augustosalonio/best_model_exercise_ii)

## Results
- Best model: DecisionTreeRegressor
- K-Fold CV (7 folds): R² ≈ 0.998, MAE ≈ 0.59 g/km
- Hold-Out: Consistent with K-Fold, confirming robust generalization