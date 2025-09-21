# Titanic - Machine Learning Prediction Model

This project uses the Titanic dataset from [Kaggle's Titanic Competition](https://www.kaggle.com/competitions/titanic) to build a machine learning model that predicts passenger survival based on demographic and travel information.

## 🔍 Project Overview

- **Dataset**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **Model**: Random Forest Classifier
- **Goal**: Predict survival (`Survived` column)

## 🛠 Features and Steps

- Missing values handled (Age & Fare using median; Embarked using mode)
- Categorical encoding:
  - `Sex` mapped to numeric (0 = male, 1 = female)
  - `Embarked` one-hot encoded
- Model trained using `RandomForestClassifier` from Scikit-learn
- Predictions saved to `submission.csv` for Kaggle submission

## 📁 File Structure

- `Titanic_prediction_model.ipynb`: Jupyter notebook with full code
- `train.csv` and `test.csv`: Original Kaggle datasets
- `submission.csv`: Output predictions for test set

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/pardhu1502/Titanic-prediction-model
   cd Titanic-prediction-model
   ```

2. Open the notebook in Jupyter or VSCode and run all cells:
   ```bash
   jupyter notebook Titanic_prediction_model.ipynb
   ```

📈 Next Steps

- Add feature engineering (e.g., extract titles from names)
- Try other models (Logistic Regression, XGBoost)
- Tune hyperparameters with GridSearchCV
- Use cross-validation for better evaluation

🧠 Author
- Maintained by: Palli Pardha Saradhi Charan
- GitHub: pardhu1502

