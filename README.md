# Customer-Churn-Prediction
Predict if a customer will leave a service (churn) based on usage data
1. *Problem Definition *  
   Define churn prediction: Identify if a customer will leave the company based on their data.

2.  *Data Cleaning*
- Check for missing values and handle them (e.g., drop or impute)  
- Convert data types correctly (like TotalCharges to numeric)  
- Encode categorical variables as numbers (using label encoding or one-hot encoding)  
- Remove irrelevant columns (like customerID)  
- Deal with duplicates if any

3. *Data Visualization*  
- Plot churn distribution (bar chart) to see class balance  
- Visualize churn vs categorical features (contract type, payment method) using countplots  
- Use histograms or boxplots for continuous features like tenure, monthly charges  
- Correlation heatmap to see relations between features  


 
4. *Data Analysis & Charts *  
   Visualize data trends like churn rate by contract type, tenure distribution, payment methods.

5. *Model Building *  
   Use models like Decision Tree, Random Forest, or XGBoost to classify churn vs. non-churn.

6. *Model Checking *  
   Evaluate with confusion matrix, accuracy, precision, recall to validate model performance.

7. *Results & Insights *  
   Highlight key factors affecting churn and how to reduce it.
