Data validation using SQL aims to ensure that the values displayed on the dashboard are accurate and correct. I use SQL Database Management to validation my own dashboard.

## Total Loan Applications
```sql
SELECT COUNT(id) AS Total_Loan_Applicant FROM financial_loan;
```
| Total_Loan_Applicant |
| -------------------- |
| 38576                |
