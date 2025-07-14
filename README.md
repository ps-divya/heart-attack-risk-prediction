
# 💓 Heart Attack Risk Prediction using Machine Learning

## 📘 Overview
Heart attacks remain a leading cause of global mortality, making early risk detection critical for effective intervention. This project presents a comprehensive machine learning pipeline to predict the likelihood of a heart attack using health survey data.

The study evaluates five classification algorithms:
- Logistic Regression  
- Naïve Bayes  
- Decision Tree  
- Random Forest  
- XGBoost

Through robust data preprocessing, feature engineering, and model evaluation, **XGBoost** emerged as the top-performing model with **96.2% accuracy** and **0.99 ROC-AUC**, highlighting the effectiveness of tree-based ensemble methods.

## 🧠 Key Features
- **End-to-end ML pipeline**: From data cleaning to model interpretation  
- **Preprocessing techniques**:
  - Missing value imputation
  - Outlier capping
  - Label encoding
  - Feature selection
  - Class balancing using SMOTE  
- **Model evaluation**: Accuracy, Precision, Recall, F1-Score, and ROC-AUC  
- **Model explainability**: Using **LIME** for local interpretation of predictions

## 🔍 Insights
- **Top predictive features**:  
  - HadAngina  
  - AgeCategory  
  - Sex  

- XGBoost consistently outperformed all other models across evaluation metrics  
- LIME explanations improved model transparency, making the predictions more interpretable for healthcare practitioners  

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy, Scikit-learn  
- XGBoost  
- LIME (Local Interpretable Model-agnostic Explanations)  
- Matplotlib, Seaborn (for visualization)

## 📊 Visual Highlights
*(plots to be added here)*

## 📁 Folder Structure
```
├── data/                # Raw and processed data
├── notebooks/           # Jupyter notebooks
├── models/              # Saved ML models
├── images/              # Visual outputs
├── README.md
```

## 📌 Keywords
Heart Attack Prediction, Machine Learning, XGBoost, Classification Models, LIME, Healthcare Analytics

