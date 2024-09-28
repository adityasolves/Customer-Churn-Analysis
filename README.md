# Exploratory Data Analysis (EDA) on Customer Churn

## Summary of EDA

### Churn Distribution
- The target variable is **Churn**, with a significant imbalance between customers who churn and those who do not.
- Visualizations like the countplot of churned vs. non-churned customers reveal that fewer customers churn compared to those who stay.

### Demographic Insights
- **Gender**: The churn rate does not show a significant difference between male and female customers, suggesting gender is not a strong predictor of churn.
- **Senior Citizen**: Senior citizens have a higher tendency to churn, indicating age plays a role in customer retention.
- **Partner and Dependents**: Customers with partners or dependents are less likely to churn compared to single customers.

### Services and Churn
- **Phone Service & Multiple Lines**: No significant correlation is observed between having a phone service or multiple lines and the churn rate.
- **Internet Services**: Customers who do not use internet services are less likely to churn. On the other hand, those using Fiber optic services have a higher churn rate, possibly due to service issues or costs.
- **Online Security, Backup, Device Protection**: Customers who subscribe to services like online security, backup, or device protection have a lower churn rate, highlighting the importance of value-added services in customer retention.

### Contract and Payment Methods
- **Contract Type**: Customers with month-to-month contracts churn more often compared to those with one or two-year contracts, indicating that longer-term commitments reduce churn.
- **Payment Method**: Customers who use electronic check payments show a much higher churn rate compared to those using other payment methods (e.g., bank transfer, credit card).
- **Paperless Billing**: Customers opting for paperless billing also tend to churn more, possibly due to less personal touch in service.

### Tenure
- Customers with shorter tenure tend to churn more frequently, whereas long-tenured customers are less likely to leave, emphasizing the importance of customer loyalty programs for new customers.

### Monthly Charges
- Higher monthly charges are associated with higher churn. This suggests that pricing strategies should be considered carefully to reduce churn, especially for higher-paying customers.

### Payment Method Analysis
- Among all payment methods, customers who pay via electronic check have the highest churn rate. This might indicate a preference for more modern, automated payment methods like credit cards or bank transfers.

## Key Conclusions
- Customers using electronic check payment are more likely to churn.
- Senior citizens and customers with month-to-month contracts are at a higher risk of churning.
- Fiber optic internet service users have a higher churn rate, potentially due to service quality or cost issues.
- Add-on services such as online security, backup, and device protection reduce churn, suggesting customers find value in these.
- Price sensitivity is apparent, as customers with higher monthly charges are more likely to leave.

The analysis highlights key areas where interventions such as pricing adjustments, promotional offers for long-term contracts, and improved service quality (especially for Fiber optic customers) could help reduce churn.
