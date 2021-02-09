# Loan Data Exploration
## by Qilin Zhang


## Dataset

- This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Please check Prosper Data Dictionary to Explain Dataset's Variables for detailed variable explanations.

## Summary of Findings

- Defaulted rate: Defaulted rate is negatively correlated with income range,  Credit Score and prosper rating. Moreover, it is positively correlated with debt-to-income ratio and Delinquencies Last 7 Years.

- Borrower rate: Borrow rate is negatively correlated with credit score and prosper rating

- Loan term strengthened the relationship between prosper rating and borrow rate. For long term loans (36 or 60 months), people with higher prosper rating could have lower rate for longer loan term.

- Loan term also strengthened the relationship between prosper rating and loan amount. People with higher prosper rating could get higher amount of loan for longer term compared to those with low prosper rating.

- For long term loans (36 or 60 months), only applications from people have credit score above 560 is granted.


## Key Insights for Presentation

- All plots are based on the cleaned dataset, which might lead to difference from the Exploration section.

- For the presentation, I focus on two questions: (1) what factors affect a loan’s outcome status, and (2) what affects the borrower interest rate in the dataset. I started by introducing four variables - loan status, borrower rate, loan amount and loan categories to provide a basic picture of these loan records.

- Afterwards, I plot the interactions between variables, which answer the research questions. Primarily, I present the plots showing the relationship between defaulted rate and credit score or Prosper rating seperately, which suggested the higher an idividual's credit score or Prosper rating, the less likely s/he might default. In the following, I use two multivariable plots to show Borrower Rate and Loan Amount by Prosper Rating and Loan Term, which is the most significant figures in the exploration section. Through these two plots, it could be discovered not only the correlation between Borrower Rate and Prosper Rating or that between Loan Amount and Prosper Rating, but also the strengthening role of loan terms on these two correlations. This answers the second research question by indicating that people with higher Prosper ratings are more likely to have lower borrower rate for longer loan term.
