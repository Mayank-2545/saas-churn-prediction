# Customer Churn Prediction and Analysis

## Project Overview
Customer churn is a critical issue for SaaS companies, leading to revenue loss and increased customer acquisition costs. This project focuses on analyzing customer data, predicting churn using machine learning, and providing actionable insights to improve retention strategies.

### Objectives
- Understand patterns and factors leading to customer churn.
- Build a predictive model to identify at-risk customers.
- Develop actionable retention strategies based on data insights.

---

## Project Structure
The repository is organized as follows:

```
├── data/                # Contains datasets (raw and processed)
├── notebooks/           # Jupyter notebooks for EDA, preprocessing, and modeling
├── scripts/             # Python scripts for data processing and modeling
├── visualizations/      # Graphs and charts created during analysis
├── results/             # Model outputs and evaluation metrics
├── README.md            # Project overview and instructions
├── requirements.txt     # Python dependencies
```

---

## Dataset
This project uses the **Telco Customer Churn Dataset** available on [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The dataset includes the following key features:

- `customerID`: Unique identifier for each customer.
- `tenure`: Number of months the customer has stayed with the company.
- `MonthlyCharges`: Amount charged per month.
- `TotalCharges`: Total amount charged to the customer.
- `Churn`: Indicates if the customer churned (Yes/No).
- `Contract`: Type of contract (Month-to-month, One year, Two year).
- `PaymentMethod`: Customer's payment method.

---

## Key Steps
1. **Data Cleaning**:
   - Handle missing values and outliers.
   - Standardize or encode categorical variables.
2. **Exploratory Data Analysis (EDA)**:
   - Visualize churn patterns across different customer segments.
   - Analyze correlations between features and churn.
3. **Feature Engineering**:
   - Create meaningful variables to improve model performance.
   - Scale or normalize numerical data as needed.
4. **Modeling**:
   - Train machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
   - Evaluate model performance using accuracy, precision, recall, and F1-score.
5. **Insights and Recommendations**:
   - Identify key drivers of churn.
   - Provide actionable strategies for customer retention.

---

## Technologies Used
- **Languages**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `xgboost`
- **Visualization Tools**: Tableau, Matplotlib

---

## Results
- **Model Performance**:
  - Achieved accuracy of X%, with a recall of Y% for identifying at-risk customers.
- **Insights**:
  - Customers with short tenure and high monthly charges are more likely to churn.
  - Month-to-month contracts have higher churn rates compared to longer-term contracts.
- **Recommendations**:
  - Implement loyalty rewards for long-term customers.
  - Proactively engage with customers on month-to-month contracts to understand their needs.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Mayank-2545/saas-churn-prediction.git
   cd customer-churn-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks or scripts for data processing and modeling.

---

## Future Scope
- Deploy the predictive model as a web application using **Streamlit** or **Flask**.
- Build a real-time dashboard for monitoring churn metrics.
- Enhance the model with additional data sources such as customer feedback and usage logs.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

