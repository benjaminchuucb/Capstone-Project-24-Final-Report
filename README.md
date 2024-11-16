# Capstone-Project-24-Final-Report

Business Problem:
Impact of Credit Card Fraud on the Bank
1. Financial Losses: Direct losses from unauthorized transactions and associated costs.
2. Customer Trust: Erosion of trust can lead to customer attrition.
3. Regulatory Compliance: Non-compliance with fraud prevention regulations can result in penalties.
Operational Costs: Increased costs due to manual review of transactions and chargebacks.


Objective: 
To develop and evaluate at least three machine learning models to accurately detect fraudulent credit card transactions, thereby reducing financial losses and enhancing customer confidence in financial institutions (e.g., credit card companies, banks, etc)


Data Collection and Preprocessing:
1. Dataset: Historical credit card transaction data containing both legitimate and fraudulent transactions.
2. Features Used:
  Numerical: amount, oldbalanceOrg, newbalanceOrig, oldbalanceDest, newbalanceDest
  Categorical: type_encoded (encoded transaction type)
3. Target Variable: isFraud (1 for fraudulent transactions, 0 for legitimate ones)
4. Data Cleaning: Handling missing values and outliers.
5. Feature Scaling: Standardization of numerical features using StandardScaler.
6. Handling Class Imbalance: Applied Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.


Models implemented:
1. Logistic Regression
2. Decision Tree
3. XGBoost Classifier


Evaluation: 
See Jupyter Notebook


Benefits of using ML Models: 
1. Early Detection: Identifying fraudulent transactions in real time to prevent losses.
2. Scalability: Handling large volumes of transactions efficiently.
3. Adaptability: Updating detection methods to counter evolving fraud tactics.


Implementation Recommendations:

Integration with Existing Systems: Deploy the model within the bank's transaction processing infrastructure.
Monitoring and Maintenance: Establish monitoring protocols to track model performance over time.
Compliance and Security: Ensure adherence to data privacy regulations during implementation.


Summary: 

Credit card fraud poses a significant threat to financial institutions, resulting in substantial financial losses and eroding customer trust. This report presents a comparative analysis of three machine learning models—Logistic Regression, Decision Tree, and XGBoost Classifier—for detecting fraudulent credit card transactions. By implementing these models, the bank can enhance its fraud detection capabilities, reduce financial losses, and improve customer satisfaction. The XGBoost Classifier emerged as the most effective model, offering high accuracy and robustness, making it the recommended choice for deployment.
