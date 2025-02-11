# Medical-Data_Visualizer
The Medical Data Visualizer is a Python project designed to analyze and visualize medical datasets using pandas, matplotlib, and seaborn. This project helps explore the distribution of age, gender demographics, and correlations between numeric features, which can be useful in medical research and healthcare analytics.

Key Features and Analysis:
Loading Data:
The program prompts the user to input the path to a CSV file containing medical data.
The dataset is loaded using pandas.read_csv(), allowing for flexible file selection.
Age Distribution Analysis:

A histogram with KDE (Kernel Density Estimation) is plotted to show the distribution of patient ages.
Helps in understanding the age spread of patients in the dataset.
Gender Distribution Analysis:

A count plot displays the number of male and female patients.
Useful for analyzing gender-based trends in medical data.
Feature Correlation Analysis:

A heatmap is generated using seaborn.heatmap() to display correlations between numerical medical features.
Helps in identifying relationships between different health indicators (e.g., age, cholesterol level, blood pressure, glucose levels, etc.).

Purpose and Applications:
Medical Research: Helps researchers understand patient demographics and feature relationships.
Healthcare Analytics: Assists in identifying risk factors and trends in patient data.
Data Exploration: Provides a visual summary before applying machine learning models.
