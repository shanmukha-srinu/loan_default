# Introduction
You are employed for a consumer finance business that specialises in providing different kinds of loans to urban clients. Upon receiving a loan application, the business must decide whether to approve the loan based on the applicant's profile. The bank's choice is subject to two different kinds of risks:

If the borrower is likely to repay the loan, refusing to provide it results in the company losing business.

If the borrower is unlikely to pay back the loan, or is likely to default, authorising the loan might result in a loss for the business.

![image](https://user-images.githubusercontent.com/36808464/198507176-eee89b49-0333-4503-ab00-e1d34c154fa3.png)

There are two possible actions the business might take in response to a loan application:

1) If the business accepts the loan, one of the following three possibilities will occur:

      1) Fully repaid: The borrower has paid off the debt in full.

      2) Current: The applicant is currently paying the monthly instalments, hence the loan's term has not yet ended.

      3) Charged-off: The applicant has been tardy in making instalment payments for a considerable amount of time.

2) Loan turned down: The loan was turned down by the business. Since the loan was denied, those applicants have no past transactions with the business, therefore this information is not accessible through the business (and thus in this dataset)

# Goal
Predict the driving factors (or driver variables) behind default. This information may be used by the business in risk analysis.


# Assumptions made:
1) if customer's home ownership mentioned as "others" they are treated under "rent" only.
2) Grade A - higher position. Grade E- lower position.

# Technologies used:
1) library-numpy,pandas, seaborn.



