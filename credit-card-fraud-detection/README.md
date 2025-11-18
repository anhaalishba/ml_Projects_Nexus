# Credit Card Fraud Detection
This project aims to **detect fraudulent credit card transactions** using machine learning.  
The dataset is highly **imbalanced**: ~99.8% normal transactions vs ~0.2% fraudulent transactions, which makes fraud detection challenging.  

We implemented two approaches:  

1. **Supervised Classification **  
   - **Random Forest + SMOTE** to handle class imbalance  
   - Focused on **Recall** and **Confusion Matrix** evaluation (Accuracy is misleading)  

2. **Anomaly Detection **  
   - **K-Means Clustering** to detect rare frauds  
   - Serves as a demonstration of unsupervised anomaly detection  

---

## 📂 Repository Structure

```

credit-card-fraud-detection/
├── fraud_eda.ipynb              # Exploratory Data Analysis
├── fraud_model_training.ipynb   # Model training (Random Forest + K-Means)
├── fraud_report.docx            # 2-page project report
├── creditcard.csv               # Dataset (or download instructions)
└── README.md                    # Project overview and instructions

````

---

## 🗂 Dataset
- **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Features:**  
  - V1–V28: PCA components of original features  
  - `Time`: Seconds since first transaction  
  - `Amount`: Transaction amount  
  - `Class`: Target variable (0 = Normal, 1 = Fraud)  

---

## 📝 Notebooks

1. **`fraud_eda.ipynb`**  
   - Performs Exploratory Data Analysis  
   - Visualizes class imbalance, transaction amount distribution, and correlations  
   - Explains challenges of imbalanced data  

2. **`fraud_model_training.ipynb`**  
   - **Random Forest + SMOTE:** Main supervised model  
   - **K-Means:** Optional anomaly detection approach  
   - Confusion matrices and Recall-focused evaluation  

---

## 📊 Key Takeaways
- Imbalanced datasets make **accuracy misleading**; focus on **Recall**.  
- Supervised learning with **Random Forest + SMOTE** detects most frauds effectively.  
- K-Means can detect anomalies but performs poorly for extremely rare frauds.  
- Handling imbalance is critical for real-world fraud detection systems.  

---

## 🚀 How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/anhaalishba/ml_Projects_Nexus/
````

2. **Install dependencies:**

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

3. **Open notebooks in Jupyter** and run cells:

   * `fraud_eda.ipynb` → Explore the dataset
   * `fraud_model_training.ipynb` → Train models and evaluate results

---
