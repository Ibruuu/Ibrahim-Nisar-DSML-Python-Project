# Ibrahim-Nisar-DSML-Python-Project
Project Overview
This project involves analyzing a dataset of employees at ABC Company. The dataset consists of 458 rows and 9 columns, including information about the employees' teams, positions, salaries, heights, and ages. The goal of this project is to preprocess, analyze, and visualize various aspects of the data to provide insights that can assist the company in understanding its workforce.

The project tasks were divided into two main parts: Preprocessing and Analysis. The preprocessing step aimed at cleaning the data, particularly correcting an error in the "height" column. The analysis section involved exploring the distribution of employees across teams and positions, investigating salary expenditures, age groups, and the correlation between age and salary. Finally, graphical representations were created for each analysis task to present the findings in an insightful manner.

Table of Contents
Preprocessing
Analysis Tasks
Team Distribution and Percentage Split
Segregation by Position
Predominant Age Group
Salary Expenditure Analysis
Correlation between Age and Salary
Graphical Representations
Insights Gained
Additional Information
Conclusion
Preprocessing
In the preprocessing phase, the "height" column was identified as containing invalid data (values outside the acceptable range of 150 to 180). To fix this, all invalid values in the "height" column were replaced with random numbers between 150 and 180. This was done to ensure data consistency and maintain the integrity of the dataset for analysis.

The preprocessing steps included:

Replacing invalid height values with random integers between 150 and 180.
Ensuring there were no missing or invalid data entries in the dataset before proceeding with the analysis.
Analysis Tasks
Team Distribution and Percentage Split
The first analysis task involved understanding the distribution of employees across the various teams. We counted the number of employees in each team and calculated the percentage split relative to the total number of employees.

This analysis provides insights into the size of each team and how resources are allocated across the company.

Segregation by Position
Next, employees were grouped based on their positions within the company. This task helps understand the number of employees in different roles, which could inform organizational structure and staffing decisions.

Predominant Age Group
The dataset contains employee age data, which was categorized into age ranges (e.g., 20-30, 30-40, etc.) to identify the predominant age group among employees. This analysis can provide insights into the age demographics of the workforce and the average career stage of employees.

Salary Expenditure Analysis
We performed an analysis to discover which teams and positions had the highest salary expenditures. This task helps identify financial trends, such as which teams or roles are the highest cost to the company and whether salaries align with the team's size and scope of responsibilities.

Correlation between Age and Salary
Finally, the correlation between employee age and salary was analyzed. This investigation helps to understand whether older employees tend to have higher salaries due to experience, seniority, or other factors. A scatter plot was created to visualize this relationship.

Graphical Representations
For each analysis task, appropriate visualizations were created to present the findings:

Team Distribution Bar Chart: Displays the number of employees across different teams.
Position Distribution Bar Chart: Shows the number of employees in various positions.
Age Group Bar Chart: Illustrates the distribution of employees across different age groups.
Salary Expenditure Bar Chart (Team-level): Shows total salary expenditure for each team.
Salary Expenditure Bar Chart (Position-level): Displays total salary expenditure for each position.
Age vs Salary Scatter Plot: Visualizes the correlation between employee age and salary.
These visualizations were created using Matplotlib and Seaborn to provide clear and informative charts that communicate the analysis results.

Insights Gained
From the analysis, several key insights were gained:

Team Distribution:

The company has a fairly balanced distribution of employees across teams, with Team X having the highest number of employees, and Team Y having the smallest. This could reflect the organizational priorities or the nature of the work within each team.
Position Distribution:

A significant portion of employees is in Position A, indicating it is a common role within the company. On the other hand, senior positions (such as Position C) have fewer employees, suggesting a hierarchical structure.
Predominant Age Group:

The most common age group is the 30-40 range, accounting for 45% of employees. This suggests the company hires a considerable number of mid-career professionals with significant experience.
Salary Expenditure:

Team X and Position A are the highest salary expenditures, which aligns with the number of employees in those teams/positions. This could be an indicator that these areas are more resource-intensive.
Age and Salary Correlation:

A positive correlation between age and salary was observed, confirming that older employees tend to have higher salaries, likely due to experience and seniority in the company.
Additional Information
The dataset used in this project was a fictional dataset from ABC Company, provided as part of the project assignment.
All data analysis was performed using Python, with the primary libraries being Pandas, Matplotlib, and Seaborn.
The analysis was conducted in a Jupyter Notebook for interactive exploration and visualization.
Conclusion
This project successfully demonstrated the process of preprocessing and analyzing a dataset to extract valuable insights. By focusing on employee data, the analysis provided insights into team distribution, position segregation, age demographics, salary expenditures, and the correlation between age and salary. The visualizations created help communicate these findings clearly and effectively.

This project not only highlighted how Python can be used to preprocess and analyze data but also emphasized the importance of data visualization in communicating insights to stakeholders.
