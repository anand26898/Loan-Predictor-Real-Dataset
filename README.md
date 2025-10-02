# Loan Predictor (Real Dataset)

## 📌 Overview

This project uses a real-world loan dataset to build a **Loan Default Prediction Model**. The dataset contains **41,029 records** with an **Outcome** column (loan paid off vs. default) and **76+ other features** collected from the loan application and applicant’s credit file at origination.

The goal is to **analyze applicant features** and build machine learning models that can predict whether a loan will be repaid or defaulted.

---

## 📂 Repository Structure

* `Tillit_Data_Science_Tech_Test.xlsx` → Original dataset
* `code.ipynb` → Jupyter Notebook with data analysis & ML modeling
* `code.pdf` → Exported PDF version of the notebook

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/anand26898/Loan-Predictor-Real-Dataset.git
cd Loan-Predictor-Real-Dataset
```

### 2. Install Dependencies

Make sure you have Python 3.8+ installed. Then install required libraries:

```bash
pip install -r requirements.txt
```

(If `requirements.txt` is missing, install commonly used ones: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, jupyter)

### 3. Run the Notebook

```bash
jupyter notebook code.ipynb
```

---

## 🧹 Data Preprocessing

* Handle missing values
* Encode categorical features
* Normalize/scale numerical features
* Feature selection/engineering

---

## 📊 Exploratory Data Analysis (EDA)

* Distribution of loan outcomes
* Correlation between applicant features and default probability
* Visualization (histograms, boxplots, bar charts, heatmaps)

---

## 🤖 Modeling

Tested/Planned Models:

* Logistic Regression
* Random Forest Classifier
* XGBoost
* Neural Networks (optional)

**Evaluation Metrics:**

* Accuracy
* Precision, Recall, F1 Score
* ROC-AUC
* Confusion Matrix

---

## 🔍 Results & Insights

* Feature importance analysis (e.g., income, credit history, loan amount)
* Risk patterns identified in defaulters vs. non-defaulters
* Best-performing ML model selection

---

## 📦 Future Work

* Hyperparameter tuning for better accuracy
* Add SHAP/LIME for model explainability
* Deploy as a Flask/Django API
* Create a web-based loan eligibility prediction dashboard

---

## 📝 Author

👤 **Anand Kumar Soni**
🔗 GitHub: [anand26898](https://github.com/anand26898)

---

## ⚖️ License

This project is for **educational and research purposes only**. Dataset should be used responsibly.
