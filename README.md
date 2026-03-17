###Experiment – 11
Bhavya Pandya
25070123139
E&TC A1

Categorical Data Analysis using Python

Aim

To analyze and interpret categorical data using Python and understand techniques for summarizing, visualizing, and drawing insights from categorical variables.

Objectives

• To understand the concept of categorical data and its types.
• To learn how to load datasets containing categorical variables using Python libraries.
• To perform frequency analysis and category-based summaries.
• To visualize categorical data using graphs and charts.
• To apply basic statistical techniques for categorical data interpretation.

Theory on Categorical Data Analysis

Categorical data refers to data that can be divided into specific groups or categories rather than measured numerically. These categories represent qualitative attributes such as gender, color, department, or product type.

In Python, categorical data analysis is commonly performed using libraries like Pandas, NumPy, Matplotlib, and Seaborn. These tools help in organizing data, calculating category frequencies, and creating visual representations.

Categorical data analysis helps identify patterns, relationships, and distributions among categories within a dataset.

1. Types of Categorical Data
Nominal Data

Nominal data represents categories that do not have any specific order or ranking.

Examples:
• Gender (Male, Female)
• Color (Red, Blue, Green)
• City names

Ordinal Data

Ordinal data represents categories that have a meaningful order but no fixed numerical difference between them.

Examples:
• Education level (School, Graduate, Postgraduate)
• Customer satisfaction (Low, Medium, High)

2. Frequency Analysis

Frequency analysis is used to determine how often each category appears in the dataset.

Python provides simple methods for frequency counting such as:

• value_counts() – Counts occurrences of each category
• groupby() – Groups data by categories for analysis

Frequency tables help in understanding the distribution of categories.

3. Visualization of Categorical Data

Visualization helps represent categorical information in a clear and understandable format.

Common visualization techniques include:

Bar Chart

Shows the frequency or count of each category.

Pie Chart

Represents the proportion of categories in the dataset.

Count Plot

Used in Seaborn to display the count of observations in each category.

These visualizations help quickly identify dominant categories and trends.

Data Handling and Processing
1. Loading the Dataset

Datasets containing categorical variables are loaded using Pandas.

Example sources:
• CSV files
• Excel files
• Online datasets

Pandas DataFrame allows easy handling of categorical columns.

2. Inspecting Categorical Variables

Basic inspection techniques include:

• Checking column data types
• Viewing unique category values
• Counting category occurrences

###Functions commonly used:

• unique() – Shows distinct categories
• value_counts() – Counts category frequency
• describe() – Gives summary statistics.

3. Data Cleaning

Before analysis, categorical data may require cleaning.

This includes:
• Removing missing values
• Standardizing category names
• Converting text values into categorical data types.

###Applications in Engineering

• Market Research: Understanding customer preferences based on categories.
• Product Classification: Grouping products by type or category.
• Quality Control: Classifying defects into categories.
• Survey Analysis: Analyzing responses collected from questionnaires.

###Conclusion

In this experiment, categorical data analysis was performed using Python. Different techniques were used to examine category distributions, perform frequency analysis, and visualize categorical variables. The experiment demonstrated how Python tools simplify the analysis and interpretation of qualitative data, making it easier to derive meaningful insights from categorical datasets.
