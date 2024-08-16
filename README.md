# Analysis-of-Indian-education-System
Self Project regarding current education system facility for the students and how it is affecting enrollment of them.
here I am working with dropout data from the Indian education system and performing data cleaning, analysis, and visualization. Here's a brief overview of what you've done and some suggestions for further steps:

Steps Taken:
Data Loading & Exploration:

You loaded the dataset containing dropout ratios from 2012 to 2015.
You explored the data using head(), columns, and identified groups by state using groupby.
Data Cleaning:

You replaced "NR" (Not Reported) values with 0 and converted columns with numeric data from string to float.
Data Filtering:

You extracted data specific to West Bengal (data_wb).
Visualization:

You used seaborn and matplotlib to create count plots, bar plots, and boxplots to visualize dropout ratios across various categories.
Outlier Detection and Handling:

You detected outliers using boxplots and handled them by clipping values between the 5th and 95th percentiles.
Suggestions:
Further Cleaning:

Ensure consistency in state names (e.g., handling both "Arunachal Pradesh" and "Arunachal Pradesh").
Check other columns for similar issues where non-numeric values like "NR" might exist.
Descriptive Statistics:

Use .describe() for numerical summaries and dataframe.info() to check data types and missing values.
Additional Visualizations:

Line Plots: Visualize trends over time for each state.
Heatmaps: Compare dropout ratios across states and years.
Statistical Analysis:

Conduct correlation analysis to see if dropout rates are related across different education levels (Primary, Upper Primary, Secondary).
Modeling:

If interested in predictive modeling, consider training a simple regression model to predict dropout rates based on previous years’ data or other features.
