# Purchase-Prediction

## 🚀 About the Project
This project analyzes online shopping trends and predicts purchase decisions based on customer behavior, preferences, and satisfaction levels. It utilizes machine learning models and Flask to create an interactive prediction web application.

---

## 🧩 Key Features
- Exploratory Data Analysis (EDA) for insights into customer demographics and behaviors.
- Predicts the likelihood of a purchase based on multiple factors like shopping frequency, income, and promotions.
- Web application powered by Flask for user interaction and predictions.
- Multiple machine learning models implemented, including:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting

---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualizations: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `imblearn`
- **Web Framework**: Flask
- **Front-end**: HTML, CSS, Bootstrap

---

## 📂 Dataset
- **Filename**: `Translated_Data_for_Analysis.csv`
- **Features**:
  - `Gender`: Male, Female, or Other
  - `Monthly Income`: Income brackets
  - `Shopping Frequency`: Frequency of online shopping
  - `Purchase Factor`: Motivations for purchasing
  - `Buy on Promotion`: Whether purchases were influenced by promotions
  - `Satisfaction Level`: Customer satisfaction levels
  - **Target Variable**: `Decision_to_Buy` (1 = Likely to Buy, 0 = Unlikely to Buy)

---

## 🔍 Exploratory Data Analysis (EDA)
- **Visualizations**:
  - Bar charts for feature distributions (e.g., gender, income levels).
  - Count plots to analyze relationships between satisfaction and other factors.
- Insights into the importance of promotions, income, and frequency on purchasing behavior.

---

## 🧠 Machine Learning Models
1. **Logistic Regression**:
   - Baseline model for predicting purchase decisions.
   - Evaluated with metrics like accuracy and AUC-ROC.

2. **Random Forest**:
   - Added robustness and feature importance analysis.
   - Visualized AUC-ROC curve for model evaluation.

3. **Gradient Boosting**:
   - High-performing model with cross-validation results.
   - Evaluated for both training and testing datasets.

4. **SMOTE**:
   - Addressed class imbalance for improved prediction accuracy.
