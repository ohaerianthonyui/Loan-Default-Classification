# Loan-Default-Classification



| Type               | Columns                                                                                                                         |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------- |
| ID info            | `ID`, `year`                                                                                                                    |
| Loan features      | `loan_limit`, `loan_amount`, `rate_of_interest`, `Interest_rate_spread`, `term`, `Upfront_charges`, `loan_type`, `loan_purpose` |
| Applicant info     | `Gender`, `Credit_Worthiness`, `income`, `Credit_Score`, `co-applicant_credit_type`, `age`                                      |
| Loan security info | `Secured_by`, `property_value`, `LTV`, `Security_Type`                                                                          |
| Loan status        | `Status` → likely the **target column** (approved/denied/default)                                                               |
| Other fields       | `region`, `dtir1`, `construction_type`, `occupancy_type`                                                                        |
