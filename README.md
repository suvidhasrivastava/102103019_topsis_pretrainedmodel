Model Performance Analysis
This repository contains a Python script for conducting TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) analysis on the performance of various machine learning models. The analysis is based on multiple metrics, and the results are visualized through bar charts.

Files and Structure:
model_performance.csv: This CSV file contains randomly generated performance metrics for different machine learning models.

TOPSIS_analysis.py: The Python script to perform TOPSIS analysis on the provided data.

result.csv: The output CSV file containing TOPSIS scores and rankings for each model.

TOPSIS_Score_comparison.png: A bar chart visualizing the TOPSIS scores for each model.

Accuracy_comparison.png, Response_Time_comparison.png, Perplexity_comparison.png, F1_Score_comparison.png, Memory_Usage_comparison.png: Bar charts visualizing the comparison of each metric across different models.

Instructions:
Run the Model Performance Script:

Execute model_performance.py to generate the model_performance.csv file with random performance metrics for different models.
Run the TOPSIS Analysis:

Execute TOPSIS_analysis.py to perform the TOPSIS analysis on the generated data and create the result.csv file.
Explore the Results:

Check the generated bar charts (TOPSIS_Score_comparison.png and individual metric charts) to visually compare the performance of different models.
Interpretation:

The result.csv file includes the TOPSIS scores and rankings for each model, providing insights into their overall performance.
Dependencies:
Python 3.x
Pandas
NumPy
Matplotlib
