# Will the Customer Accept the Coupon? 
- README

## Overview
This project analyzes customer behavior to determine the factors influencing whether a driver accepts a Coffee House coupon while driving. Using data from the UCI Machine Learning Repository, the analysis explores key variables such as time of day, weather, income levels, and coupon expiration time.

## Dataset Description
The dataset contains various features including:
- Demographic attributes (age, income, marital status)
- Contextual attributes (driving destination, passengers, weather, time of day)
- Coupon attributes (expiration time, type of establishment)
- Behavioral patterns (frequency of coffee shop visits, restaurant preferences)
- Acceptance Outcome (whether the driver accepted the coupon or not)

## Analysis Summary
This project utilizes Python libraries such as **pandas, seaborn, and matplotlib** to analyze the data and create meaningful visualizations. The analysis focuses on:
1. Time of Day Effect - Identifying peak times when drivers accept coffee coupons.
2. Weather Influence - Examining how different weather conditions impact acceptance rates.
3. Income Factor - Understanding how budget-conscious drivers respond to discounts.
4. Expiration Timing - Comparing acceptance rates between 2-hour and 1-day expiration coupons.

## Key Findings
- Morning and Midday Preference: The highest acceptance rates occur at **10 AM (64.07%)** and **2 PM (54.79%)**, suggesting that coffee consumption is more frequent during these hours.
- Weather Impact: Drivers are more likely to accept coffee coupons on **days that are not snowing**, with higher acceptance rates on rainy (**52.21%**) and sunny (**50.36%**) days, compared to snowy days (**43.23%**).
- Income and Discounts: Drivers earning **less than $50K** accept coffee coupons more frequently (**52.25%**) compared to higher-income groups.
- Expiration Time Matters: Coupons with a **1-day expiration (58.39%)** are accepted more often than those expiring in **2 hours (43.20%)**.

## How to Run the Notebook
1. Clone or download this repository.
2. Ensure you have **Python 3.x** installed along with the required libraries:
  
   pip install pandas numpy seaborn matplotlib
   
3. Open the Jupyter Notebook:
   
   jupyter notebook prompt.ipynb
  
4. Run all cells in order to generate the results and visualizations.

## Next Steps & Recommendations
- Further analysis could include **machine learning models** to predict coupon acceptance with higher accuracy.
- Additional data on **driver preferences and motivations** could improve insights.
- Businesses can use these findings to **optimize digital coupon strategies**, targeting users at peak hours and offering longer expiration times for higher engagement.


