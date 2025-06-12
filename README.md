# 🚢 Titanic Survival Prediction using Machine Learning

This project uses the Titanic dataset from Kaggle to predict whether a passenger survived or not based on features like age, gender, class, fare, etc. It covers the full machine learning workflow from data cleaning to model evaluation and feature importance analysis.

---

## 📂 Dataset
- Source: [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- train.csv and test.csv files used for building and testing the model.

---

## 📌 Project Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values (Age, Embarked, Cabin)
   - Encoded categorical variables
   - Dropped irrelevant features (like Name, Ticket)

2. **Exploratory Data Analysis (EDA)**
   - Visualized survival rates by gender, class, age groups, etc.
   - Found patterns like females had a higher survival rate

3. **Feature Engineering**
   - Created new features like FamilySize, IsAlone
   - Converted categorical variables using One-Hot Encoding / Label Encoding

4. **Model Building**
   - Tried multiple models: Logistic Regression, Decision Tree, Random Forest
   - Tuned Random Forest with GridSearchCV

5. **Evaluation**
   - Accuracy, Confusion Matrix, Precision, Recall, F1-score
   - Selected best model based on accuracy and balance between metrics

6. **Feature Importance**
   - Visualized which features influenced the prediction most (like Sex, Fare, Pclass)

---

## 🧠 Best Performing Model

- **Model:** Random Forest Classifier (after hyperparameter tuning)
- **Test Accuracy:** ~81%
- **Top Important Features:** Sex, Fare, Pclass

---

## 📊 Libraries Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

---

## 📎 How to Run

1. Clone the repo
2. Open `Titanic_Prediction_Model.ipynb` in Jupyter/Colab
3. Run all cells

---

## 📌 Result Snapshot

> Confusion Matrix, Classification Report, and Feature Importance chart included in notebook.

---

## ✅ Status
✔️ Completed  
🚀 Future Scope: SHAP visualizations, Web App deployment
