## EDA on lending company loan data.
 Lending Company is an online loan marketplace, facilitating personal loans, business loans, and financing of medical proceduresBorrowers can easily access lower interest rate loans through a fast online interface. 

lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. borrowers who default cause the largest amount of loss to the lenders.

## Business Objectives 

the objective of this EDA study is to understand the driving factors (or driver variables)
behind loan default, i.e. the variables which are strong indicators of default.Identification of such applicants using EDA is the aim of this case study.

Introduction
Section 1: UNDERSTANDING THE DATA
Section 2: DATA CLEANING AND INITIAL ANALYSIS
Section 3:Plotting Correlations between continous variables
Section 4:Plotting Association among variables
Section 5:Analyzing Outliers( Visualization)
Section 6:Imputing Missing Value
Section 7: Findings


## General Information
I have used Loan dataset provided by Upgrad. datset has 111 variables.

## Technologies Used
pandas- 1.2.4
Numpy- 1.20.1
SeaBorn -0.11.1
Sweetviz-2.1.3

## Findings
#### Loan status plot clearly highlights 6.5 to 1  of Fully paid to defaulters' ratio. 
#### Company has been making one loss to every 6.5 non defaulting account
#### home ownership plot shows that majority of the borrowers are Rented/mortgage
#### Verification status plot shows that company has been accepting non verified  customers compared to verified and source verified.
#### Purpose plot shows that majority of the loans are borrowed for debt consolidation.
#### Grade A and B loan are distributed  proportionately more than other grades.
#### Sub grades' A4, A5,B3,B5,C2 are distributed proportionately higher than other sub grades.
#### Demand of 36 months loan has been almost 3 times the demand of 60 months loan.
#### Company has been funding more loan to 10+ years of employment length than other years. Company has relatively lesser customer with employment length of 8 
#### Proportion of fully paid to defaulters are much better in 36 months term than 60 months.
#### Proportion of fully paid to defaulters are much better in grade A,B and C than grade E,F,G.
#### Grade G is the worst performer.
#### Subgrades’ A4,A5,b3,B4,B5 are best performers whereas G5,G3,F5 are worst performers.
#### Default risk across the home ownership level is low.
#### Proportion of fully paid to defaulters are considerably similar at all level of employment length.
#### Proportion of fully paid to defaulters are much better in verification status of non verified better than verified and source verified.
#### Default risk is considerably negligible where the purpose have been Moving, Vacation, and educational.
#### Median loan amount is higher for defaulters.
#### Median DTI is higher for Defaulters.
#### Median Interest rate is higher for defaulters.
#### Median Income for non defaulters are high.
#### defaulter and fully paid customers have grown from 2007 to 2011.
#### defaulter and fully paid customers have grown from January to December
#### Employee title such as Lockheed martin, USAF ,Wells Fargo, Walgreenshave perform better 
#### Walmart is the worst performer.
#### no outliers in DTI
#### High outliers in Annual income and loan amount.
#### DTI has normal distribution
#### Installment, Annual income, amount funded by lending club, Loan amount, amount funded by investor and interest rate are positively skewed.
#### Skewed variables have now normal distribution after log1 transformation as we managed the outliers efficiently without dropping them.
#### State such as California, new York , Texas and Florida have state where company are experiencing high number of fully paid as well as defaulters.
#### There is not much difference in interest rate among  different level of work experience.
#### loan amount has been higher for employment length of 10 years.
#### Strong Correlation between loan amount, amount funded by investor, amount funded by LC and installment.
#### Interest rate, grade and sub grade shows strong association among each other, and they form a segment with strong association.

## Recommendations
#### Company should fund more loans with 36-month term as there are lesser defaulters compared to 60-month loan term.
#### Company should fund more loans with Grade A,B and C  as there are lesser defaulters.
#### Company should halt it’s funding for Grade G loans as it performs worst among all grades.
#### Company should focus on Subgrades’ A4,A5,b3,B4,B5 as these are best performers whereas put stringent criteria for G5,G3,F5 as they are worst performers.
#### Company should increase the interest rate for borrowers with less than 5 years of employment level as there is not much difference in interested rate across the employment level. 
#### Company should lend more to borrowers with purpose: Moving, Vacation, and educational as default has been negligible in this segment.
#### Company should fund more loan for borrowers with higher income with employment level of at least 5 years.
#### Company should revisit their funding strategy for verified and source verified borrowers .Surprisingly non verified borrowers have performed better.
#### Five variables : Interest rate, Term, Grade, Sub Grade and Annual Income are most significant driving factors. 







## Contact
Created by [@charliethomasct82] - feel free to contact me!


