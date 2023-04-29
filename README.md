I used interactive charts in my project in order to see it properly please use this link: 

# Online store - A/B testing Project
Using A/B test to find the best hypotheses that may help boost revenue

## Description:
As an analyst at a major online store, the objective of this project is to collaborate with the marketing department in order to increase revenue. This will be achieved by prioritizing a list of compiled hypotheses, conducting A/B testing, and analyzing the results to determine the most effective strategies. The project will follow a structured approach that involves hypothesis prioritization, implementation of the chosen hypothesis through a well-designed A/B test, and data-driven evaluation of the test outcomes to identify and implement the most impactful revenue-boosting initiatives.

## Project goal:
1. Prioritize the hypotheses
2. Launch an A/B test
3. Analyze the results
4. Make a recommendation

## Methodology:
### Prepearing the data:
1. Cheking the overview data.
2. Checking the data for missing values, duplicates and outliers.
3. Check if data types are right.
4. Data preprosscing and calculcation.
### The research:
1. Use the RICE and ICE methods to prioritise the hypotheses.
2. Cumulative Revenue Analysis: Plot cumulative revenue by group and draw conclusions.
3. Cumulative Average Order Size Analysis: Plot cumulative average order size by group and draw conclusions.
4. Relative Difference Analysis: Plot relative difference in cumulative average order size for group B compared to group A and draw conclusions.
5. Conversion Rate Analysis: Calculate and plot daily conversion rates for each group, comparing differences and drawing conclusions.
6. Orders per User Analysis: Create a scatter chart of orders per user and draw conclusions.
7. Anomaly Detection for Orders per User: Calculate the 95th and 99th percentiles, defining the anomaly threshold.
8. Order Prices Analysis: Create a scatter chart of order prices and draw conclusions.
9. Anomaly Detection for Order Prices: Calculate the 95th and 99th percentiles, defining the anomaly threshold.
10. Statistical Significance Analysis: Evaluate the significance of differences in conversion and average order size between groups using raw and filtered data.
11. Decision Making: Based on the test results, decide whether to stop the test and declare a winner, stop the test and conclude no difference, or continue the test.

## Libraries:
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- plotly.express
- stats from spicy
- math
