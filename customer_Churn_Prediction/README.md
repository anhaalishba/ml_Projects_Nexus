# 📊 Customer Churn Prediction 
This project predicts **customer churn** for a telecom company using four different machine learning models.  
Churn means whether a customer will **leave the service (Yes)** or **stay (No)**.

The project includes:
- Full Exploratory Data Analysis (EDA)
- Data preprocessing & feature encoding
- Model training & evaluation
- Accuracy comparison of 4 ML models
- Confusion matrix analysis
- Final project report in DOCX

---

## 📁 Project Structure

```

customer-churn/
│
├── churn_eda.ipynb
├── churn_model_training.ipynb
├── churn_report.docx
├──  Telco-Customer-Churn.csv   
└── README.md

````

---

## 📘 Dataset

**Telco Customer Churn Dataset**  
Contains customer information such as:
- Contract type  
- Monthly charges  
- Tenure  
- Payment method  
- Internet service  
- Demographics  
- Target: `Churn` (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:
- Dataset overview (`info`, `describe`, missing values)
- Churn distribution
- Feature relationships such as  
  - tenure vs churn  
  - contract type vs churn  
  - monthly charges vs churn  
- Correlation heatmap
- Visual insights using Seaborn & Matplotlib

File: `churn_eda.ipynb`

---

## 🤖 Machine Learning Models

We trained and compared these four classification models:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **XGBoost Classifier**

Each model was evaluated using:
- Confusion Matrix  
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Classification Report  

File: `churn_model_training.ipynb`

---

## 🏆 Model Comparison

A comparison table includes the evaluation metrics for all four models.  
This helps identify the best-performing model based on:

- Higher Recall  
- Better F1-score  
- Balanced Precision  
- Fewer false negatives in confusion matrix  

---

## 📄 Report

A 2-page project report is included explaining:

- What churn prediction is  
- Summary of EDA findings  
- Performance of each model  
- Which model performed best  
- What was learned  

File: `churn_report.docx`

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run the Project

1. Clone the repository
  
````

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks:

   ```bash
   jupyter notebook
   ```

4. Run:

   * `churn_eda.ipynb`
   * `churn_model_training.ipynb`
