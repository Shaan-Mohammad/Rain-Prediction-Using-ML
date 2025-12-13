# Rain Prediction in Australia using Machine Learning

## 📌 Project Overview
This project predicts whether it will rain the next day in Australia using historical weather data.
Multiple supervised machine learning algorithms are applied and compared after careful preprocessing
to avoid data leakage and ensure reliable evaluation.

## 📊 Dataset
- Source: Australian Weather Dataset
- Records: ~142,000
- Target Variable: RainTomorrow (Yes/No)

## ⚙️ Preprocessing Steps
- Removed leakage-prone features (RainToday, RISK_MM)
- Dropped high-missing columns
- Handled missing values using median/mode
- One-hot encoded categorical features
- Feature scaling using StandardScaler
- Train-test split with stratification

## 🤖 Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Linear Support Vector Machine (LinearSVC)

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC
- k-Fold Cross-Validation

## ✅ Key Findings
- Linear models (Logistic Regression, Linear SVM) performed robustly.
- Humidity and pressure were the strongest predictors of rainfall.
- Initial perfect accuracy was due to target leakage, which was identified and fixed.

## 🧠 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📌 Note
This project was developed as part of a Predictive Analytics academic assessment and follows syllabus-approved methods only.
