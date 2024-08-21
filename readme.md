# Lending Club Case Study
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the bank’s decision:
    1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company:

  1) Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
      1) Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      2) Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
      3) Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
  2) Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Public record of bankruptcy or derogatory is a very big indication of the potential defaulter.
- Most number of defaulters carry a revolving line utility of 34% or above. This is against a recommended 30%.
- The annual income of the fully paid are slightly higher than the defaulters. Low income paired with higher interest rates is a deterring factor for the non-repayment.
- The defaulters have made more number of inquiries with various credit institutions and were not entertained. This is an indication that those banks see a red flag in these customers.
- Though the numbers are less, people with ‘Other’ type of home ownership tend to default more.
- Customers who tend to have borrowed for 'Small Business' top the list of defaulters. This is followed by Renewable energy and Education. 
- Though few customers from Nevada, there seems to be more defaulters, at a distance followed by Nebraska and Arkansas at close range.
- The high Debt-to-income ratio combined with Low Income range contribute to more defaulters
- Interest rate of the defaulters are higher than their fully-paid counter parts. This could be as a result of loss mitigation towards potential defaulting.
- Highest income range and lowest debt-to-income ratio makes better candidates for good loans.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter - version 1.0.0
- Python - version 3.11.9
- numpy - version 1.26.4
- Pandas - version 1.5.3
- matplotlib - version 3.8.0
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was provided by upgrad for EDA case study


## Contact
Created by [@prscsy] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
