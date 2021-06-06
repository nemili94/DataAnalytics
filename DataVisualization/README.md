# data_visualization


# Exploration of Prosper Loan Data
## by Milica Nesic

## Dataset

ProsperLoanData dataset contains data from almost 85000 loans and 81 loan variables in the US for the period from November 2005 until March 2014. For the purpose of my exploration, I focused on the data after July 2009, since the categorization of the data changed for this point onwards. My focus was on exploring how Borrower Rate, Term of Loan (duration of the loan) and Prosper Rating (the loan risk) affect the approved Loan Amount.

Dataset can be found in my github repository: https://github.com/nemili94/data_visualization/blob/main/prosperLoanData.csv
with the variable descriptor: https://github.com/nemili94/data_visualization/blob/main/Prosper%20Loan%20Data%20-%20Variable%20Definitions.xlsx


## Summary of Findings

Through the exploration I found there is a significant correlation between Prosper Rating and the Borrower Rate. Lower Risk loans are given at a lower Borrower Rate, while the higher risk ones were given at the higher Borrower Rate. Also, with the increase in Term duration the Borrower Rate goes up as well, due to the uncertainty of time. Interesting to see, as well, was the negative correlation between Prosper Rating and the Loan amount. However, the relationship between the two variables does not seem to be linear - at lower Loan Amounts we can find rates of all levels, but as the Loan Amounts increase the Borrower Rate decreases. My conclusion wouldn't be that Loan Amount affects the Borrower Rate, but rather that there are other variables that affect the both variables in a opposing manner. <br>

My key takeaway would be that in conditions of longer Terms and lower ProsperRatings low amount Loans are approved with higher rates As the prosper ratings improve, and the Terms shorten  higher loan amounts are approved with lower rates.

## Key Insights for Presentation

I start the presentation by introducing the main variable of interest, Borrower Rate, and explain it distribution and main points. After that I show the distribution of the Loan Amounts and briefly mention other categorical variables. <br>

Then, I introduce the heatmap representing relationship between two main numeric variables Borrower Rate and Loan Amount, followed by two groupped bar plots showing each of these variables in relationship to categorical variables - Term and ProsperRating. <br>

I end the presentation with FacetGrid plot of multiple plots showing relationships of all category variable combinations with Borrower Rate and Loan Amount in form of scatterplots.
