# Titanic Survival Prediction

This repository contains code for predicting survival on the Titanic using machine learning models. The project includes data preprocessing, feature engineering, model selection, hyperparameter tuning with GridSearchCV, and evaluation metrics optimization.

## Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the RMS Titanic sank after colliding with an iceberg, resulting in the death of 1502 out of 2224 passengers and crew. In this competition hosted on Kaggle, the challenge is to build a predictive model that answers the question: "what sorts of people were more likely to survive?" using passenger data such as name, age, gender, socio-economic class, etc.

### Kaggle Competition Details

For more information about the competition and discussions, visit the [Titanic Kaggle Competition Discussion Forum](https://www.kaggle.com/competitions/titanic/discussion?sort=hotness).

## Project Structure
- `train.csv`, `test.csv`: Titanic dataset files used for training and testing.
- `submission.csv`: Predicted survival outcomes for the test set.
- `Titanic_Prediction.ipynb`: Jupyter notebook containing the project code.
- `requirements.txt`: Python dependencies required to run the project.

## How to Use
1. Clone the repository: `git clone https://github.com/SakshiFadnavis2003/titanic-survival-prediction.git`
2. Navigate to the project directory: `cd titanic-survival-prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the Jupyter notebook `Titanic_Prediction.ipynb` to explore the code and predictions.
5. Modify and experiment with the code to improve the model or try different algorithms.

## Dependencies
- pandas
- numpy
- scikit-learn
- imbalanced-learn

