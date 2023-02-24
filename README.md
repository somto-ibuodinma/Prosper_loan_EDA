# Part I - Exploring Loan Dataset from Prosper

## by IBUODINMA SOMTOCHUKWU I


## Dataset

>This data set contains various loans and certain charateristics that relates to the debtors.It is a dataset taken in a particular period in time.
Although it contains several variable (81 precisiely).
I intend to select some variables of interest and apply them to vizualization methods.
It is intended that productive insights will be generated from the dataset the source of your data and summarize any data wrangling steps that you performed before you started your exploration.


## Summary of Findings
>I am interested in the following variables and how they affect the various loans listed. They are

>Term: The distibution of this variable is skewed to the left. Although, the variable is numerical, its discrete nature imposes category on it, making it amenable to be analysed as a categorical variable.

>LoanStatus: Thus is purely a categorical variable, it is skewed to the left. Most borrowers are owing or have paid up their loans. No unusual points observed.

>BorrowerRate: There distribution approached normal distribution except for the high count between 0.3 and 0.35. Basically, most of the loans are within interest rate ranging from 0.10-0.25 (10%-25%). We see an anomaly at 0.35-0.4. Why? With bivariate or multivariate plots we will discern what happened as we compare with other variables.

>BorrowerAPR: There distribution approached normal distribution except for the high count between 0.35 and 0.4. Basically, most of the loans are within APR ranging from 0.15-0.3 (15%-30%). We see an anomaly at 0.35-0.4. Why? We bivariate or multivariate plots we will discern what happened as we compare with other variables.

>EmploymentStatus: We have more Employed and full-time workers taking loans

>IsBorrowerHomeowner:There is not much observable significance in the distibution of this column. It seems home ownership does not have much impact of whether one will borrow or not.

#### Certain relationships were observed among the variables. They include

>**loan Status vs Annual Percentage rate:** Borrowers who have completed their loans had the highest annual rate followed by those who defaulted. The completed loans has the list median and most of the rates are within the interquatile range (The completed loans seem to have favourable rates between the lowest and the upper quartile, the maximum not withstanding- could it be a reason for the borrowers paying up.The defaulted registered a narrower range and a higher median, suggesting higher rates than those that are completed. further, the current loans seem promising as the rates are more lesser for most of its data points.

>**loan Status vs Annual Percentage rate:** The defaulted and charged off loans show a significantly high rates, suggesting a possible reason for the failures to payback. The Current and Completed loans show more points within the IQR. The completed loans mostly so because we see rates as low as zero a possible incentive to borrow.

>**APR vs Interest Rate:** The APR and interest rate showed clear direct proportionality as expected.

>**Employment Status vs Loan Status:** For completed loans,full time followed by employed are more. For current loans, Employed aee singnificantly more. It seems that self employed and the rest are not amenable to these loans.

>**Employment Status vs APR:** Regarding maximum and minimum APR, there seem to be uniform distribution among the job categories. except for the outliers in the Not available group.However, unemployed people have APRs that within higher range.
The borrowers choice of loans where not influenced home ownership as seen in the second plot


>In the multivariate plot of APR vs Interest Rate, we see that the application of a third variable LenderYield clearly brought out the direct proportionality of the initial variables of interest namely (APR and interest rate). The higher the two variables the more the profit from the loans to investors.this makes sense.

>The borrowers choice of loans where not influenced home ownership as seen in the second plot

>In the 3rd plot, self employed, fulltime, employed, part time and retired borrowers, tend to pick loans with low interest rates

>Finally, most of the job categories tend to take up the 36-month loans other the interest rates are a bit higher than the other two terms. Most of the job catetegories tend to take loans with terms of 36 and 60 months.

## Key Insights for Presentation

> The focus of this thread will the interest rate in relation to other variables of interest.

> For the distribution of interest rates approached normal distribution except for the high count between 0.3 and 0.35. Basically, most of the loans are within interest rate ranging from 0.10-0.25 (10%-25%). We see an anomaly at 0.35-0.4.

> The defaulted and charged off loans show a significantly high rates, suggesting a possible reason for the failures to payback. The Current and Completed loans show more points within the IQR. The completed loans mostly so because we see rates as low as zero a possible incentive to borrow.

> The APR and interest rate showed clear direct proportionality as expected

> The Lender yield on the loan. Lender yield is equal to the interest rate on the loan less the servicing fee. Here, there is a marked propornality among the three numerical variable. The color encoding for the third variable showed an upward progression as the rates increases. This is expected.

> Finally, most of the job categories tend to take up the 36-month loans other the interest rates are a bit higher than the other two terms. Most of the job catetegories tend to take loans with terms of 36 and 60 months