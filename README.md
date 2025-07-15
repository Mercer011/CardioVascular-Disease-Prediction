# CardioVascular-Disease-Prediction


# 🫀 Cardiovascular Disease Prediction using Machine Learning

This project aims to predict the risk of **cardiovascular disease** using supervised machine learning models. Using a real-world healthcare dataset of over 70,000 patient records, the model can assess the likelihood of a person having heart-related issues based on medical features like age, blood pressure, cholesterol levels, and more.

---

## 📌 Project Highlights

- ✅ Supervised ML models: **Decision Tree, Random Forest, XGBoost**
- 📊 Dataset: ~70,000 patient records
- ⚙️ Preprocessing: Null handling, outlier removal, feature engineering, scaling
- 🧪 Evaluation metrics: **Accuracy, Precision, Recall, F1-score, ROC-AUC**
- 📈 Best Accuracy: **76%** (using XGBoost)
- 📉 Visualization: Confusion matrix, ROC curve, feature importance
- 🧠 Simulated predictions for real-world demo input

---

## 🔧 Tools & Technologies

- Programming Language: **Python**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`
- Jupyter Notebook for development

---

## 📂 Dataset

- Publicly available healthcare dataset
- ~70,000 rows and multiple medical features including:
  - Age
  - Systolic and Diastolic Blood Pressure
  - Cholesterol
  - Glucose
  - Smoking/Alcohol Status
  - Physical Activity

> *(Dataset source and license details, if public, can be added here)*

---

## 🚀 How It Works

1. **Data Cleaning**
   - Removed duplicates, handled missing values
   - Handled outliers using IQR method

2. **Feature Engineering**
   - Created new features (e.g., BMI categories, cholesterol levels)
   - Performed one-hot encoding for categorical variables

3. **Model Training**
   - Trained Decision Tree, Random Forest, and XGBoost classifiers
   - Tuned hyperparameters using cross-validation

4. **Model Evaluation**
   - Evaluated with multiple metrics: Accuracy, F1-score, ROC-AUC
   - Visualized confusion matrix and ROC curve

5. **Demo Predictions**
   - Simulated patient inputs for real-time prediction with confidence scoring

---

## 📊 Sample Output

### 🔹 Confusion Matrix

![Confusion Matrix](path/to/your/confusion_matrix.png)

---

### 🔹 ROC Curve

![ROC Curve](path/to/your/roc_curve.png)

---

### 🔹 Prediction on Sample Input

| Age | BP | Cholesterol | Smoking | Alcohol | Activity | Predicted Risk | Confidence |
|-----|----|-------------|---------|---------|----------|----------------|------------|
| 52  | 140| 240         | No      | No      | Yes      | High Risk      | 87%        |

---

## 📁 Folder Structure

