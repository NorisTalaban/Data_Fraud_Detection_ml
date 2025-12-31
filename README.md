# Credit Card Fraud Detection

## Project Description
This is a personal fraud detection project developed using a very large and highly imbalanced dataset.  
The goal is to detect fraudulent transactions while handling class imbalance and understanding customer behavior patterns.

---

## Model Choice
After testing several models, **XGBoost** proved to be the most effective due to its:
- Strong performance  
- Flexibility in handling different types of features  
- Interpretability through feature importance analysis  

---

## Methodical Approach
The workflow followed in this project is classic for fraud detection, but with a focus on **readability and clarity**:

1. **Data Loading & Exploration** – inspecting the dataset, checking for missing values, and understanding the target distribution.  
2. **Feature Engineering & Preprocessing** – creating meaningful features while keeping the code and data structure readable.  
3. **Dataset Balancing** – applying SMOTE to address class imbalance.  
4. **Model Training & Evaluation** – training the XGBoost classifier and assessing performance using metrics such as AUC, F1-score, precision, and recall.  
5. **Data Visualization** – All visualizations are placed at the end of the workflow to keep the code clean and readable. However, visual analysis and exploring the data structure were among the **first steps** used to guide feature engineering and create meaningful features.


## Value of Domain Knowledge
Professionals in fraud detection can leverage domain expertise to design more sophisticated features, detect behavioral anomalies, and identify subtle fraud schemes more effectively.

## Code Implementation
- Written inline in a single notebook for **immediate readability**.  
- No pipelines or modularization to keep the workflow easy to follow, especially for learners or reviewers.  
- All steps, from data cleaning to model evaluation, are clearly documented.  
