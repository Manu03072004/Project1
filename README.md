# Building Damage Prediction During an Earthquake

## Project Overview
This project predicts the mean building damage after earthquakes using an XGBoost regression model.  
It includes data preprocessing, feature encoding, model training, evaluation, and visualizations.  
This project can help in disaster planning by estimating structural vulnerability.

## Features
- Loads and cleans the earthquake building damage dataset.
- Converts categorical features to numerical using one-hot encoding.
- Trains an XGBoost regression model to predict mean building damage.
- Evaluates model performance using:
  - Mean Absolute Error (MAE)
  - R-squared (R²)
- Visualizes:
  - Feature correlation heatmap
  - Actual vs Predicted damage scatter plot
  - Top 10 feature importance
- Easy to modify and extend for other regression tasks.

## How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/) or download it locally.
2. Install required Python packages (if running locally):
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn xgboost
    ```
3. Run all cells in the notebook to reproduce results.

## Dataset
- The dataset file `15.eq_building_damage.csv` is included in the repo.
- The CSV contains features such as:
  - `year_built` – Year the building was constructed  
  - `struct_typ` – Type of building structure  
  - `occ_type` – Occupancy type  
  - `meandamage` – Target variable representing mean damage
- File path in the notebook:
   ```python
   file_path = "15.eq_building_damage.csv"
   ```
   
## Files
- `Building_Damage_Prediction.ipynb` — Main notebook containing code and outputs  
- `15.eq_building_damage.csv` — Dataset file  
- `README.md` — This project description file  

## Author
[**Pusarla Manaswini**](https://github.com/Manu03072004)  
Email: pusarlamanaswini@gmail.com



