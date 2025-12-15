# Amazon-Sales-Analysis
I managed to create an analysis on Amazon product sales from Q4 data
The Problem Statement

For my analysis, I chose to focus on a question regarding Amazon product sales in the last fiscal quarter. After searching online for relevant datasets, I found one on Kaggle that specialized in Amazon products. The central question I developed is: "Which product categories generated the most revenue in different geographic regions during the last quarter (Q4 2024)?"

It is important to recognize that data is always in a constant demand for company insights, and the e-commerce revolution is a consistently interesting factor to consider, given that consumers are constantly purchasing products on Amazon on a weekly, monthly, and yearly basis. Therefore, I thought it would be insightful to determine which regions generated the most successful revenue over the past quarter.

Methodology and Summary
Data Cleaning and Filtering: The first step in this analysis was the Data Cleaning and Filtering process. I ensured that column titles were spelled correctly. I also checked the 'Price' and 'Discount Percentage' columns to confirm there were no missing values. Additionally, I filtered the data to include only completed orders in Q4 2024 using Python with the Pandas library.

Data Aggregation: The next step was Data Aggregation, where I calculated the total revenue sum, split by Region and Category. I managed to execute this process using SQLite within a Google Colab (Jupyter) notebook environment.

Visualization: Finally, I created code to formulate a visualization, presenting the grouped sales data as a Bar Chart using the Matplotlib and Seaborn libraries.

Findings: To summarize the big findings what I found particularly was the fact that North America as a continent spends the most out of the other regions in the past fiscal year, with $6,317.68 spent in the clothing category. While Australia and Asia were spending more in the Home & Kitchen category, where Australia spent $5,775.32 and the ladder Asia spent $4,987.15. This could mean a number of things comparing western culture to the east could be a clash of ideas.  It can be known that America even as a nation is always known for its fashion trends and people will often purchase a lot of clothing during holiday months (October - December). Regions like Asia are recognized both for their famous cuisines and for a cultural structure where home life is central. Families prioritize the home as the center for activity and for creating lasting memories.

