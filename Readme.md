# Student Performance Data Analysis

## Problem Description

The goal of this project is to generate and analyze student performance data using Python. The dataset includes 10,000 students with random attributes such as:
- *Name* (Generated using Faker library)
- *Department* (Randomly chosen from CSE, ECE, IT, EEE)
- *Year* (1st to 4th year)
- *Marks in Subjects* (Electronics, Mathematics, DSA, Programming, Database, Data Science)

### Tasks Involved:

1. *Data Generation:*
   - Use Faker to create student names.
   - Randomly assign departments and academic years.
   - Generate subject marks (ranging from 30 to 100).
   - Store the data in a Pandas DataFrame and save it as a CSV file.

2. *Data Analysis & Visualization:*
   - Compute subject-wise correlations and visualize using a heatmap.
   - Identify pass/fail counts per subject.
   - Compute the average marks of each student.
   - Convert marks into CGPA (scale of 10).
   - Display summary statistics.
   - Visualize CGPA distribution using histograms.

3. *Data Processing with Parallel Computing:*
   - Implement a Mapper function to extract subject-wise marks.
   - Utilize multiprocessing to parallelize data extraction.

4. *Predictive Modeling:*
   - Use Linear Regression to predict a student’s overall performance based on subject marks.
   - Display regression coefficients for each subject.

5. *Ranking Students:*
   - Identify top 10 and bottom 10 students based on average marks.

### Expected Output:
- A CSV file containing the student dataset.
- Statistical analysis of student performance.
- Visualizations for correlation and CGPA distribution.
- A trained linear regression model.
- Lists of top and bottom performing students.

This project integrates data generation, analysis, parallel computing, machine learning, and visualization techniques to explore student performance insights effectively.
