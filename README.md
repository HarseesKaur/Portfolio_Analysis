# Portfolio_Analysis
This is a Portfolio Analysis of stocks of FAANG companies. I have analyzed and defined specific functions(refer ReadMe file) on various metrics such as - Overall stock performance, monthly returns, expected returns of each asset in the portfolio along with their associated risks among various others. Hope it's informative for you'll :)


ASSIGNMENT QUESTIONS 

Create the code for each of the three functions listed below and write a report based on the code as described.
Function 1: This function takes a time series of a fund as input and outputs the key performance statistics, both as numbers and graphically. 	
Name: 	fund_performance()
Input: 	A monthly performance time series N*1 NUMPY array.
The array can be an index or price returns, and if price returns it can be either decimal or percentage – the function must decide which it is.
Output: 	1. A 3x1 NUMPY array with the key performance statistics.
		2. Display, with formatting, the key performance statistics. 
		3. A time series plot of the index
		4. A histogram of the monthly returns

Function 2: This function takes the weights, expected return of each asset in a portfolio and outputs the expected return and risk of the portfolio. 
Name: 	expected_performance()
Input: 		1. Weights as an Nx1 NUMPY
		2. Expected Returns as an Nx1 NUMPY array
		3. A VCV matrix as a NxN NUMPY array

Output: 	1. A 2x1 NUMPY array with the ER and risk of the portfolio.
		2. Display, with formatting, the ER and risk of the portfolio.
		3. Save the output array as a csv file with the name calculated _perfomance.csv

Function 3: This function draws the efficient frontier of a four-asset portfolio, given risk and expected return of each asset in the universe.
Name:	draw_efficient_frontier()	
Input: 		1. Expected Returns as an 4x1 NUMPY array
		2. A VCV matrix as a 4x4 NUMPY array

Output: 	1. A plot of the efficient frontier.

Notes:
You may only use the MATPLOTLIB and NUMPY packages for this – you may not use any other package.
The key performance statistics are Annual Return (%), Annualised Volatility (%) and Sharpe Ratio.
You should also create code to call each of the functions with the required data.
You must be able to explain every line of your code – random students may be interviewed in the assessment stage.



