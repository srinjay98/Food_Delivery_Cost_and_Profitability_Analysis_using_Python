Project Description :
Analyzing food delivery order data to evaluate cost structure, profitability, and simulate optimal discount–commission strategies using Python.

Technologies Used :
Python 3.x
Pandas – for data cleaning, manipulation, and aggregation
Matplotlib – for visualizing revenue, cost, and profit metrics
Seaborn – for advanced distribution and comparison plots
Google Colab – for running and visualizing analysis


Project Workflow:

1) Data Loading & Preprocessing :
   Loaded the dataset (food_orders_new_delhi.csv) using pandas.
   Converted date/time columns into proper datetime objects.
   Extracted discount values (both fixed ₹ and % types) using string parsing.

2) Feature Engineering :
   Computed derived columns like:
   Discount Amount
   Total Costs
   Revenue
   Profit
   Calculated profitability and commission percentages per order.

3) Profitability Analysis
   Visualized profit distribution across orders using histograms and KDE plots.
   Created cost proportion pie charts and revenue–cost–profit bar charts.

4) Simulation of Recommended Rates
   Applied recommended 30% commission and 6% discount.
   Compared simulated vs. actual profitability using Seaborn density plots.
   
5)Outputs & Visuals
     Profit Distribution Plot – shows order-wise profit variation
     Cost Breakdown Pie Chart – proportion of delivery, processing, and discount costs
     Revenue vs. Costs Bar Chart – compares overall metrics
     Simulated Profitability Curve – compares actual vs. recommended rates
   
