# JPMC-Virtual-Internship
This is a repository that contains the tasks for the JP Morgan & Chase Software Engineering Virtual Internship offered by Forage. The goal was to visualize stock price data using JPMC's own visualization tool named 'Perspective' to help traders by giving insights on trading stratergies.

# Task 1 - Interface with a stock price data feed
We’ve been asked to assist with some development to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks.
The trader would like to be able to monitor two historically correlated stocks and be able to visualize when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). 

This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

Before implementing this request using perspective, first we’ll need to interface with the relevant financial data feed and make the necessary adjustments to facilitate the monitoring of potential trade opportunities.
