# ncaa-basketball-stats

This repo contains the Jupyter Notebooks, datasets, and saved model files for a data science project using 2023–24 NCAA women’s basketball player statistics.

The project walks through a complete data science workflow: data acquisition, cleaning, preprocessing, feature engineering, exploratory data analysis, visualization, model selection, model training, and model evaluation. The dataset includes individual player statistics such as points, rebounds, assists, blocks, steals, shooting percentages, and derived metrics.

Project overview: [Basketball Data Science Project](https://www.pineconedata.com/projects/basketball-data-science-project/)

## Project articles and notebooks

### 1. Project Setup and Data Acquisition

* [Full article](https://www.pineconedata.com/2024-04-11-basketball-data-acquisition/)
* Notebook

  * [`1_data_acquisition.ipynb`](/notebooks/1_data_acquisition.ipynb)
* Dataset(s)

  * [`2024-04-07 NCAA WBB-Div1 Player Info.csv`](/data/2024-04-07%20NCAA%20WBB-Div1%20Player%20Info.csv)
  * [`player_info.xlsx`](/data/player_info.xlsx)
  * [`player_stats.xlsx`](/data/player_stats.xlsx)
  * [`player_data_raw.xlsx`](/data/player_data_raw.xlsx)

### 2. Data Cleaning and Preprocessing

* [Full article](https://www.pineconedata.com/2024-05-02-basketball-data-cleaning-preprocessing/)
* Notebook

  * [`2_data_cleaning_preprocessing.ipynb`](/notebooks/2_data_cleaning_preprocessing.ipynb)
* Dataset(s)

  * [`player_data_raw.xlsx`](/data/player_data_raw.xlsx)
  * [`player_data_clean.xlsx`](/data/player_data_clean.xlsx)

### 3. Feature Engineering

* [Full article](https://www.pineconedata.com/2024-05-30-basketball-feature_engineering/)
* Notebook

  * [`3_feature_engineering.ipynb`](/notebooks/3_feature_engineering.ipynb)
* Dataset(s)

  * [`player_data_clean.xlsx`](/data/player_data_clean.xlsx)
  * [`player_data_engineered.xlsx`](/data/player_data_engineered.xlsx)

### 4. Exploratory Data Analysis

* [Full article](https://www.pineconedata.com/2024-06-28-basketball-data-exploration/)
* Notebook

  * [`4_data_exploration.ipynb`](/notebooks/4_data_exploration.ipynb)
* Dataset(s)

  * Uses [`player_data_engineered.xlsx`](/data/player_data_engineered.xlsx). No new dataset was created.

### 5. Data Visualizations

* [Full article](https://www.pineconedata.com/2024-07-29-basketball-visualizations/)
* Notebook

  * [`5_data_visualization.ipynb`](/notebooks/5_data_visualization.ipynb)
* Dataset(s)

  * Uses [`player_data_engineered.xlsx`](/data/player_data_engineered.xlsx). No new dataset was created.

### 6. Selecting a Machine Learning Model

* [Full article](https://www.pineconedata.com/2024-08-12-basketball-select-ml-ols/)
* Notebook

  * [`6_model_selection.ipynb`](/notebooks/6_model_selection.ipynb)
* Dataset(s)

  * Uses [`player_data_engineered.xlsx`](/data/player_data_engineered.xlsx). No new dataset was created.

### 7. Training a Linear Regression Model

* [Full article](https://www.pineconedata.com/2024-09-13-basketball-train-ols/)
* Notebook

  * [`7_model_training.ipynb`](/notebooks/7_model_training.ipynb)
* Dataset(s)

  * Uses [`player_data_engineered.xlsx`](/data/player_data_engineered.xlsx)
  * [`X_train_full.csv`](/data/X_train_full.csv)
  * [`X_train_few.csv`](/data/X_train_few.csv)
  * [`X_test_full.csv`](/data/X_test_full.csv)
  * [`X_test_few.csv`](/data/X_test_few.csv)
  * [`y_train_full.csv`](/data/y_train_full.csv)
  * [`y_train_few.csv`](/data/y_train_few.csv)
  * [`y_actual.csv`](/data/y_actual.csv)
* Model(s)

  * [`model_full.sav`](/models/model_full.sav)
  * [`model_few.sav`](/models/model_few.sav)

### 8. Evaluating a Linear Regression Model

* [Full article](https://www.pineconedata.com/2024-11-27-basketball-evaluate-ols-model/)
* Notebook

  * [`8_model_evaluation.ipynb`](/notebooks/8_model_evaluation.ipynb)
* Dataset(s)

  * [`X_test_full.csv`](/data/X_test_full.csv)
  * [`X_test_few.csv`](/data/X_test_few.csv)
  * [`y_actual.csv`](/data/y_actual.csv)
  * [`y_pred_full.csv`](/data/y_pred_full.csv)
  * [`y_pred_few.csv`](/data/y_pred_few.csv)
  * [`y_pred_base.csv`](/data/y_pred_base.csv)
* Model(s)

  * [`model_full.sav`](/models/model_full.sav)
  * [`model_few.sav`](/models/model_few.sav)

## Bonus article

### Ridge Regression vs. OLS Linear Regression

* [Full article](https://www.pineconedata.com/2025-04-04-ridge-regression-vs-ols-linear-regression-models/)
