# creditscoring-segmentation

Credit scoring and segmentation involve assessing the creditworthiness of individuals or businesses and categorizing them into specific groups.

Dataset:
Age: This feature represents the age of the individual.
Gender: This feature captures the gender of the individual.
Marital Status: This feature denotes the marital status of the individual.
Education Level: This feature represents the highest level of education attained by the individual.
Employment Status: This feature indicates the current employment status of the individual.
Credit Utilization Ratio: This feature reflects the ratio of credit used by the individual compared to their total available credit limit.
Payment History: It represents the monthly net payment behaviour of each customer, taking into account factors such as on-time payments, late payments, missed payments, and defaults.
Number of Credit Accounts: It represents the count of active credit accounts the person holds.
Loan Amount: It indicates the monetary value of the loan.
Interest Rate: This feature represents the interest rate associated with the loan.
Loan Term: This feature denotes the duration or term of the loan.
Type of Loan: It includes categories like “Personal Loan,” “Auto Loan,” or potentially other types of loans.

Here we evaluated the credit scores using FICO formula:
A FICO® score is a particular brand of credit score. A credit score is a number that is used to predict how likely you are to pay back a loan on time.
35% weight for “Payment History”, 
30% weight for “Credit Utilization Ratio”, 
15% weight for “Number of Credit Accounts”, 
10% weight for “Education Level”, 
and 10% weight for “Employment Status”. 
