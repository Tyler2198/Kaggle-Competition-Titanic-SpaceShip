# Passenger Survival Prediction on SpaceTitanic 🚀
This project aims to predict passenger survival (Transported) aboard the fictional SpaceTitanic spaceship using machine learning techniques. The notebook explores data preprocessing, feature engineering, model training, evaluation, and preparation of submission results.

## Project Overview 📊
This project uses data from a hypothetical competition where participants predict the survival of passengers based on various features. The main objectives include:

- Data preprocessing to handle missing values and categorical variables.
- Feature engineering to create new informative variables.
- Building a robust machine learning pipeline using XGBoost.
- Evaluating the model performance with metrics like accuracy and classification reports.

## Dependencies 🛠️
To run this notebook, you need the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- xgboost
- sklearn

## Features and Engineering ✨
The dataset includes various numerical and categorical features such as:

- Numerical: Age, RoomService, FoodCourt, etc.
- Categorical: HomePlanet, CryoSleep, VIP, etc.
Feature engineering was applied to create new features:

- Interactions between features (RoomService_CryoSleep, HomePlanet_Deck).
- Normalization of numerical data for better model performance.

## Model and Evaluation 📈
### Model
- The main model used is XGBoost Classifier, chosen for its efficiency with tabular data.
- Hyperparameters like learning_rate, max_depth, and n_estimators were set for optimal performance.
### Evaluation
- 5-Fold Cross-Validation was conducted to ensure robust model training.
- Final model performance was assessed using:
  - Accuracy: 81.3% on the hold-out set and 80.33% on test set.
  - Classification Report: Provides detailed precision, recall, and F1-score for both classes.
