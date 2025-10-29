# 📘 Loan Default Prediction using Machine Learning  

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?logo=Jupyter&logoColor=white)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E.svg?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c.svg?logo=plotly&logoColor=white)](https://matplotlib.org/)

---

### 🧠 Overview  
In today’s global economy, financial institutions such as banks and lending agencies provide millions of loans to individuals and businesses. While issuing loans is a vital source of revenue, it also carries a major risk — the risk of **loan default**.  

A **loan default** occurs when a borrower fails to make scheduled payments, leading to significant financial losses for lenders. With the rising number of defaulters, accurate **risk assessment** has become a crucial part of the loan approval process.  

Traditional manual evaluations are often slow, biased, and limited.  
This is where **Machine Learning (ML)** plays a transformative role — by analyzing large volumes of historical data, ML can uncover hidden risk patterns that humans might overlook.

---

### 🎯 Objective  
To build a **predictive model** that classifies loan applicants as either:
- **Default Likely**
- **Non-Default Likely**

This project enables financial institutions to:
- ⚡ Automate loan risk assessment  
- 💰 Adjust interest rates dynamically  
- 🏦 Reduce non-performing assets (NPAs)  
- 📊 Improve profitability through data-driven decision-making  

---

### 🧩 Features
- Data cleaning, preprocessing, and EDA  
- Feature engineering to extract key risk indicators  
- Model training using multiple ML algorithms  
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  
- Feature importance visualization  

---

### 🧰 Tech Stack

| Category | Tools & Libraries |
|-----------|-------------------|
| **Language** | Python |
| **IDE** | Jupyter Notebook |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost |
| **Version Control** | Git, GitHub |

---

### 📊 Workflow
1. **Data Collection** → Import loan dataset  
2. **Data Preprocessing** → Handle nulls, outliers, categorical variables  
3. **EDA** → Visualize and understand trends  
4. **Feature Engineering** → Encode and scale important features  
5. **Model Building** → Train ML models (Logistic Regression, Random Forest, XGBoost, etc.)  
6. **Evaluation** → Analyze model metrics and compare performance  
7. **Prediction** → Classify new loan applicants  

---

### 📈 Model Performance  
- Random Forest & XGBoost achieved high accuracy and stable performance.  
- Feature importance shows that **Credit History**, **Loan Amount**, and **Applicant Income** strongly influence default probability.  

### 🖥️ How to Run the Project

## 🪜 Step 1: Clone the Repository
git clone https://github.com/SwatiMane02/Loan-Default-Prediction.git
cd Loan-Default-Prediction  

## 🪜 Step 2: Create and Activate Virtual Environment (optional but recommended)
# Create environment  
python -m venv venv  

# Activate it  
# On Windows:  
venv\Scripts\activate  
# On macOS/Linux:  
source venv/bin/activate  

## 🪜 Step 3: Install Dependencies
pip install -r requirements.txt  

## 🪜 Step 4: Run the Jupyter Notebook
jupyter notebook  

Then open the file: 👉 **Loan_Default_Prediction.ipynb**

## 🪜 Step 5: Run All Cells
Follow the notebook sequentially to:  
- 🧹 Preprocess data  
- 🤖 Train models  
- 📊 Evaluate performance  
- 🔮 Generate predictions
  
---

## 👩‍💻 Author
**Swati Mane**  
Web & Android Developer | AI/ML Enthusiast  
🔗 [GitHub Profile](https://github.com/SwatiMane02)
