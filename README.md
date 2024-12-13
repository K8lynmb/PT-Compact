# PT-Compact
Physical Therapy Workforce Data Analysis
This project analyzes the workforce data for physical therapists across different states in the United States, with a focus on comparing states that are part of the Physical Therapy Interstate Compact. The analysis involves cleaning the data, performing exploratory data analysis (EDA), and creating visualizations to gain insights into the distribution and trends of physical therapists in PTCompact and non-PTCompact states.

Project Overview
The dataset used in this project contains state-by-state information about the number of physical therapists, with a focus on comparing the workforce in states that participate in the PT Compact. The goal is to clean the dataset, merge additional information if available, and visualize key trends and differences between PTCompact and non-PTCompact states.

Requirements
Before running the analysis, you will need the following Python libraries installed:

pandas: For data manipulation and analysis.
numpy: For numerical operations.
matplotlib: For creating static, animated, and interactive visualizations.
seaborn: For statistical data visualization.
openpyxl: For reading and writing Excel files.

Features

Data Cleaning:

Handling Missing Values: The code handles missing values by dropping rows or filling missing values with zeros.
Removing Duplicates: Ensures that there are no duplicate rows in the dataset.
Correct Data Types: Ensures the 'Number of Physical Therapists' column is correctly formatted as numeric values.
Bar Plot: Compares the total number of physical therapists in PTCompact vs non-PTCompact states.
Trend Line: Visualizes the trend of physical therapist numbers over time, broken down by PTCompact status.
Heatmap: A state distribution heatmap shows the number of physical therapists per state and whether the state is part of PTCompact.
Results Interpretation
Bar Plot: This visualization provides a clear comparison between the total number of physical therapists in PTCompact and non-PTCompact states. It helps identify which group has a higher concentration of physical therapists.

Trend Line: The trend line chart helps you analyze how the number of physical therapists in PTCompact and non-PTCompact states has evolved over time. It can highlight whether PTCompact states have seen a growth or decline in the number of physical therapists.

Heatmap: The heatmap offers a visual summary of the state distribution and the workforce concentration in each state. This can be helpful in identifying regional trends and disparities in the number of physical therapists.
