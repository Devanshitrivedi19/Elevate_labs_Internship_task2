
# 📊 Exploratory Data Analysis (EDA) – Titanic Dataset

## ✅ What I Did

- **Loaded the cleaned Titanic dataset** and reviewed basic statistics and structure using `.info()` and `.describe()`.

- **Boxplots**  used to compare numerical features (`Age`, `Fare`) across categorical variables like:
  - `Pclass` (Passenger class)
  - `Sex_male` (gender, one-hot encoded)
  - `Survived` (target variable)

- **Pairplot** was generated to visually inspect relationships between key numeric features (`Age`, `Fare`, `Pclass`) with the `Survived` label.

- **Correlation Heatmap** was used to analyze linear relationships between features and identify any potential multicollinearity.

- **Survival Patterns and Trends:**
  - Compared survival rate based on gender, passenger class, Fare, and Age using countplots and boxplots.
  - Reconstructed the `Embarked` column from one-hot encoded variables to analyze survival by embarkation port using a custom decoding function and countplot.

## 🧠 Observed Patterns

- **Gender**: Female passengers had significantly higher survival rates.
- **Passenger Class**: 1st class passengers had the highest survival rate.
- **Fare**: Passengers who paid higher fares were more likely to survive.
- **Age**: Younger passengers had a slightly higher chance of survival.
- **Embarkation Port**: Passengers embarking from Cherbourg (C) had a higher survival rate compared to other ports.

## 🛠 Tools Used

Python,
Pandas, Matplotlib, Seaborn, Scipy

## 📁 Dataset

The dataset used was the preprocessed version: `Cleaned-Titanic-Dataset.csv`.
The raw dataset for Titanic Dataset use is from: (https://www.kaggle.com/datasets/yasserh/titanic-dataset)
---
