# Python-Challenge-3

**Utilize Python, Pandas and API's to create a financial planner for emergencies and retirement situations**

`Background`

You’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. You just won your first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.

`What You're Creating`

You’ll create two financial analysis tools with a single Jupyter notebook:

A financial planner for emergencies. The members will be able to use this tool to visualise their current savings. The members can then determine if they have enough reserves for an emergency fund.

A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

# Answers to Questions about analysis done:

`What are the lower and upper bounds for the expected value of the portfolio with a 95% confidence interval?`

The lower and upper bounds for the expected value of the portfolio with a 95% confidence interval are:

95% CI Lower      0.966581

95% CI Upper     13.366098

`Using the current value of the stock and bond portion of the member's portfolio, as well as the summary statistics that you generated from the new Monte Carlo simulation, what are the lower and upper bounds for the expected value of the portfolio (with the new weights) with a 95% confidence interval?`

95% CI Lower      0.680161

95% CI Upper      5.417249

`Will weighting the portfolio more heavily toward stocks allow the credit union members to retire after only 10 years?`

Based on the CI upper and CI lower bound calculations comparison between the 30 year investment portfolio and the 10 year portfolio, with a larger initial investment of $60,000 in the 10 year portfolio, the range of investment outcomes in terms of returns, of being more heavily weighted in stocks offers a higher minumum and maximum return, meaning it would allow the credit union members faster than the 30 year portfolio weighting, which is more evenly weighted between stocks and bonds.
