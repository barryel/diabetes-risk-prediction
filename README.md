# 🩺 Early-Stage Diabetes Risk Prediction  

This project predicts the likelihood of early-stage diabetes in patients using **PySpark ML**.  
It applies a **Design Thinking approach** (with empathy mapping) to frame the problem from a healthcare and patient-experience perspective.  

---

## 🚀 Project Overview
- **Goal:** Build a predictive model that classifies whether a person is at risk of diabetes based on medical attributes.  
- **Approach:**  
  1. **Empathy Mapping (Design Thinking)** → Understanding patients’ struggles and healthcare challenges.  
  2. **Data Preparation** → Cleaning, handling missing values, encoding categorical data.  
  3. **Modeling with PySpark ML** → Logistic Regression, Random Forest, Decision Tree.  
  4. **Evaluation** → Accuracy, Precision, Recall, F1-score.  

---

## 📂 Repository Structure
- `notebooks/` → Jupyter notebooks (exploration + modeling)
- `data/` → (optional) dataset folder (excluded in .gitignore)
- `src/` → source code (functions, scripts)
- `reports/` → results, visualizations, documentation
- `requirements.txt` → list of Python libraries
- `README.md` → project documentation
- `.gitignore` → ignored files (cache, datasets, .DS_Store)

---

## 🛠️ Tools & Libraries
- **Python**, **PySpark (pyspark.ml)**  
- pandas, numpy, scikit-learn  
- matplotlib / seaborn  
- Jupyter Notebook (or Databricks)

---

## ▶️ How to Run Locally
# 1. Clone the repo
git clone https://github.com/barryel/diabetes-risk-prediction.git
cd diabetes-risk-prediction

# 2. Create a virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run Jupyter Notebook
jupyter notebook notebooks/diabetes.ipynb


