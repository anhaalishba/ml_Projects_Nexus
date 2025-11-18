```markdown
# Mall Customer Segmentation
This project performs **customer segmentation** for a mall using **unsupervised learning (K-Means clustering)**. The goal is to identify distinct customer groups based on **annual income** and **spending habits**, helping the marketing team design **targeted promotions and strategies**.

## Dataset
- **Source:** Mall Customer Dataset  
- **Features:**  
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1-100)

## Key Concepts
- **Exploratory Data Analysis (EDA)**: Visualizing distributions and relationships.  
- **K-Means Clustering**: Using the Elbow Method to find the optimal number of clusters.  
- **Cluster Interpretation**: Understanding customer behavior in each cluster.

## Repository Structure
```

mall-customer-segmentation/
│
├── mall.csv                  
├── segmentation_eda          
├── segentation_nodel_training          
├──segmentation_report               
├── README.md


````

## Key Insights
- **Cluster 0:** High income, low spending (“Big Savers”)  
- **Cluster 1:** High income, high spending (“Premium Customers”)  
- **Cluster 2:** Medium income, medium spending (“Average Customers”)  

This segmentation helps the marketing team **target each group effectively**, improve customer engagement, and design tailored marketing campaigns.

## How to Run
1. Clone the repository:  
 
````

2. Open the notebooks in **Jupyter Notebook** or **Google Colab**.
3. Run all cells to reproduce the analysis, clustering, and visualizations.

