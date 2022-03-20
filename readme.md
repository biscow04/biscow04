# (ProsperLoan Data Exploration)
## by (Adebayo Ishola)


## Dataset

> The data consists of information regarding 113937 of loanees at prosperloan, including many columns. 
  The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv).


## Summary of Findings

> In the exploration, I found that the Borrower rate is the main reason why loanees are attracted to ProsperLoan to get a loan. I was able to establish that the investors invest more in people who work Full-time and Employed than other options of employment. By this, the investors can make more profits although not all features favor them. The Borrower APR has a similar effect as the Borrower rate.

> Outside of the main variables of interest, I check LP Customer Payments and LP Customer Principa Payments to see the correlation with Credit Grade. What I observed was amazing as this shows the highest grade AA to have a huge rise in the LP Customer Principa Payments



## Key Insights for Presentation

> For the presentation, I have to do some data wrangling. I drop some rows and columns with little or no use for them. I also rename the columns and column with value NaN to N/A. The rows and columns with NUll values dropped too.

> For the presentation, I focus on 4 of numeric variables (borrower_rate, borrower_apr, lender_yield, and investors) and 2 of the categorical variables (employment_status and credit_grade). Start by introducing the four numeric variables. On borrower_rate, borrower_apr, lender_yield, and investor standard scale was used. The logarithm scale was used on investors too. Then I use the violin plot to determine if the employment_status feature affects the Borrower. Did the same for investors using a violin plot, This was the stage I introduced the categorical variables.

> Afterward, I use the scatter plot to observe the relationship between borrower_rate, borrower_apr, and lender_yield. I then introduce employment_status and credit_grade by using the Faceset regplot to plot the distribution. I maintained a good eyesight color so it was easy to read.