# Customer Churn Prediction (Machine Learning)

This project builds an end-to-end **customer churn prediction** system using a real-world telecom dataset.  
It is designed as a **portfolio project for Data Analyst / Machine Learning / BI roles**.

---

## Dataset

### Source (Important)
**This project uses the IBM Telco Customer Churn dataset**, which is a **real-world dataset published by IBM and widely used for machine learning training and industry case studies**.

The dataset is publicly available and commonly used in:
- IBM Data Science learning programs
- University machine learning courses
- Industry churn prediction demonstrations

### Why this dataset is realistic
The dataset reflects real telecom customer behavior and includes:
- Customer tenure
- Contract type
- Monthly and total charges
- Subscribed services
- Payment methods
- Churn indicator (Yes / No)

These attributes closely match real subscription-based business data.

---

## Dataset Handling (Auto-Download)

To ensure reproducibility and ease of use:

- The notebook first checks if the dataset exists locally.
- If not found, it automatically downloads the CSV file from IBM’s public GitHub repository.
- The dataset is then saved locally and loaded for analysis.

This approach ensures the project can be run on any machine without manual setup.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow
1. Load and validate the real dataset
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature engineering
5. Train/test split
6. Model training (Logistic Regression, Random Forest)
7. Model evaluation (Confusion Matrix, ROC-AUC)
8. Model comparison and selection
9. Save best-performing model
10. Business insights and recommendations

---

## Key Insights
- Customers on **month-to-month contracts** show significantly higher churn.
- **Lower tenure customers** are more likely to churn.
- **Higher monthly charges** are associated with increased churn risk.
- Contract type and tenure are strong churn predictors.

---

## Business Recommendations
- Focus retention strategies on new and month-to-month customers.
- Offer incentives for early-tenure users.
- Use churn probability scores to prioritize customer outreach.

---

## Files in This Repository
- `customer_churn_prediction_ml.ipynb` – Main ML notebook
- `Telco-Customer-Churn.csv` – Dataset (auto-downloaded)
- `best_churn_model.pkl` – Saved model (optional)

---

## How to Run
1. Clone the repository
2. Open the notebook in Jupyter
3. Run all cells  
   (The dataset will download automatically if not present.)

---

## Future Enhancements
- Model explainability (SHAP)
- Cost-based churn modeling
- Threshold tuning for business objectives
