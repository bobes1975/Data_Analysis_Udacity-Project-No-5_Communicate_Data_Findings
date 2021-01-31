# Project: Data Visualization

## Author: Robert HROMADA (SVK)


### ProsperLoan Data Exploration


### Dataset description

Prosper or Prosper Marketplace Inc. is a San Francisco, California <a href="#[3]">[3]</a> based company specializing in loans at low interest rates to the borrowers.

Prosper Loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.  Not all of them require to be analyzed.

All data are explained in dictionary provided by Prosper Loan.

Dataset contains a lot of messy and tidy data. But the goal for this project is not to clean all findings. 

Our effort will be focus on facts which have impact on borrowers’ request for loan from Prosper Loan.

Due to fact that Prosper Loan business area is Loan Providing, we can expect that they need to be sure that borrower will be able to:
* pay regularly for its loan,
* has appropriate income for appropriate loan high.


### Data cleaning and Data analysis

During this part of our project we will focus only on basic cleaning of our dataset. Main effort will be givven to visualisation of our findings.

### Exploration of dataset / Explanatory analysis

As we mentioned above primary interest of Prosper Loan is to create profit from loan providing service. Therefore, we expect that that Prosper Loan wants to be responsible and company will properly evaluate their new clients - borrowers.

Generally, during the exploration phase we will focus on following questions:

*How was changed the loaned amount of money changed on yearly basis?

*What is the most common loan lenght and loan high?

*What features of borrower will have impact on loan? We can expect that huge impact will have background of the borrower e.g. occupation, monthly or yearly income, whether they are with homeowner status and prosper rating.

*What was the reason for loan?


### Summary of Findings

* Global financial crises strongly affected loan business in 2009 <a href="#[1]">[1]</a> and in 2014 <a href="#[2]">[2]</a> as well.

* Top 5 "Loan Region" are California, Texas, New York, Florida and Illinois.  California is a leader probably due to fact that Prosper Loan was founded and is located in California.

* Most common Loan Amount are 4000 USD followed by 15000 and 10000 USD.

* Prosper Loan offer three terms for Loan. Most common lenght is 36 months.

* Main reason for loan is Debt Consolidation. It looks a little bit strange to take money to pay previous one but in case e.g. that "BorrowerRate" is lower that the previous one or borrower try to consolidate his/her debt is understandable.

* Borrower with occupation has regular income. They are better client regarding Prosper Loan risk.

* More than 50% of borrowers have income between 25.000 - 74.999 USD.

* StatedMonthlyIncome influences ProsperScore for borrowers in positive way. Higher income causes higher ProsperScore and easier loan approval process.

* Borrowers with higher ProsperScore has lower borrower rate. Outliers could be due to other factors such as amount of loan taken, new monthly income or employment status or some others.

* Same pattern is visible with CreditScoreRange vs. ProsperRatingAlpha. For rating AA we can see higher CreditScoreRandge than for HR rating.

* Strong correletion between MonthlyLoanPayment and OriginalLoanAmount. From the loan provider point of you is expected to agree with loan for borrower with suitable income.

* Ownership of house is not a factor for loan and it was not in the past neither.

* ProsperRatingAplha has direct impact on relation between BorrowerRate and EstimatedReturn.

* Higher MothlyLoanPayment allows higher LoanOriginalAmount and short Term for paying whole Loan.

* LoanOriginalAmout depends on IncomeRange. 

* Higher IncomeRange is an indicator that client is able to fulfil loan commitment.

* Client with rating "E" or "HR" are not allowed to have o loan higher than 5 000 USD even in case of higher IncomeRange.

* Best candidates for loan are those who are employed and have rating AA to C.

* In every EmploymentStatus category s clearly visible that ProsperRating is increasing with increasing StatedMonthlyIncome. 

* LoanOriginalAmount and MonthlyLoanPayment has very good linear relationship for each Term.

* Clients with EmploymentStatus as "Self employed" and "Part time" are not allowed to take loan higher than 20 000 USD.

* "Self employed" are allowed to have a loan more offen than "Part time" clients.

* Clients with EmploymentStatus as "Not employed" or "Not available" are too risky for a loan.


### Slide deck deliverable

In our final slide deck deliverable, we will focus on these points from our analysis:

* How has Prosper Loan business changed over years?
* Who are the Prosper Loan customers?
* What is the preferable lenght for loan?
* Who is the best candidate for Prosper Loan from the POV of the company?
* Which features are highly impactful for approval of loan status?
* What is the main reason for the acquiring the loan?

We can easily say that major insights obtained are:
* EmploymentStatus
* StatedMonthlyIncome
* ProsperScore
* ProsperRatingAplha.

Will explain how these factors affect decition of Prosper Loan to agree with loan for borrowers.


<a id='Resources'></a>
## Resources

<a id="[1]">[1]</a> <a href="https://en.wikipedia.org/wiki/Global_financial_crisis_in_2009">Global financial crisis in 2009</a>

<a id="[2]">[2]</a> <a href="https://www.oecd.org/economy/growth/the-effect-of-the-global-financial-crisis-on-oecd-potential-output-oecd-journal-economic-studies-2014.pdf">The effect of the global financial crisis
on OECD potential output</a>

<a id="[3]">[3]</a> <a href="https://www.prosper.com/plp/about/contact-us/">Prosper Funding LLC</a>
