# User Behavior Analysis | python + Tableau

End-to-end analysis of user behavior across traffic channels, device types, subscription status, and geography. The project examines engagement metrics (sessions, account creation, email verification), sales dynamics, and applies statistical testing to identify significant differences between user segments.

Link to Tableau: [Customer Behavior Dashboard](https://public.tableau.com/views/CustomerBehavior_17720571039910/CustomersDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Description

The goal of this project was to analyze how user behavior and purchasing patterns differ across key segments such as traffic channels, device types, subscription status, and geography. The analysis focuses on engagement metrics (sessions, account creation, and email verification) as well as sales dynamics, with statistical tests used to validate whether observed differences between segments are statistically significant.

One of the main challenges of this project was identifying all relevant dimensions that could influence overall results. 

During the analysis, I gained practical experience selecting appropriate statistical methods for different types of data and analytical questions, including correlation analysis and statistical tests for differences between groups.

## Main Stages

- First, I wrote SQL queries (executed from python) to extract all the necessary data from the dataset.

- The analysis was conducted in Google Colab. The initial steps included data understanding and data cleaning. During the cleaning stage, I checked the dataset for missing values, replaced NULL values in the `browser_language` column with `"undefined"`, and converted the `date` column to the appropriate datetime format.

- Next, I performed exploratory data analysis and applied statistical tests to validate the statistical significance of the findings, including correlation analysis and tests for differences between user segments. For visualizations, I used Matplotlib and Seaborn.

- After completing the analysis, I exported the cleaned dataset to Tableau and created an interactive dashboard that summarizes the key results in one place.



## Dashboard

![Customers Dashboard](/Customers%20Dashboard.png)
