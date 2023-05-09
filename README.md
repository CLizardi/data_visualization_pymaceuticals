# Data Visualization with PyMaceuticals
![myriam-zilles-KltoLK6Mk-g-unsplash](https://user-images.githubusercontent.com/52866379/237008718-dd782a7a-6ab6-4013-adba-052cf3df8a37.jpg)

# Introduction
Welcome to the Data Visualization with PyMaceuticals project! In this project, I utilized Matplotlib to visualize and analyze a real-world dataset for a pharmaceutical company that specializes in anti-cancer medications.

# Project Overview
As a senior data analyst for Pymaceuticals, Inc., I was tasked with analyzing a complete dataset from a recent animal study that tested potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. The goal was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens. My tasks included generating all the tables and figures needed for the technical report of the clinical study and providing a top-level summary of the study results.

# What I Did
In this project, I performed the following tasks:

Prepared and cleaned the dataset by merging mouse_metadata and study_results DataFrames and removing duplicate data
Generated summary statistics that included mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen
Created bar charts and pie charts to visualize the total number of rows and distribution of female and male mice in the study
Calculated quartiles, found outliers, and created a box plot to visualize the distribution of the final tumor volume for all the mice in each treatment group
Created a line plot and a scatter plot to visualize the tumor volume versus time point for a single mouse treated with Capomulin and mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen, respectively
Calculated correlation and regression to analyze the relationship between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

# Tools Used
The following tools were used in this project:

* Python - for scripting and data analysis
* Jupyter Notebook - for writing and executing the Python code
* Matplotlib - for data visualization and analysis
* GitHub - for version control and collaboration
* VSCode - for writing and editing markdown files.

# What I Learned
Through this project, I gained experience in the following:

* Using Matplotlib to visualize and analyze data
* Generating summary statistics for a dataset
* Identifying outliers and creating box plots to visualize distribution
* Analyzing the relationship between variables using correlation and regression
* Collaborating on GitHub and using VSCode for writing and editing markdown files.

# Analysis
249 mice conducted by Pymaceuticals revealed some insights. The sex distribution of the mice were rougly equal, with 50% being male and 50% being female. Additionally, 9 different drug regimens were tested, including a placebo. Out of all these drug regimens, Ramicane appeared to be the most effective at reducing tumor growth, as it had the lowest mean, median, variance, and standard deviation among the tested drugs. Capomulin was also effective, and both drugs had the highest number of timepoints. The correlation and regression analysis revealed a strong positive relationship between tumor volume and mouse weight, with a correlation of 0.84. Overall, Ramicane and Capmulin were found to be the most effective drugs in reducing tumor growth among the tested regimens.

# Conclusion
In conclusion, the Data Visualization with PyMaceuticals project allowed me to gain hands-on experience in analyzing and visualizing real-world datasets using Matplotlib. I was able to generate summary statistics, create bar and pie charts, identify outliers, and create box plots to visualize the distribution of the final tumor volume for each treatment group. I also gained experience in creating line and scatter plots and analyzing the relationship between variables using correlation and regression. Overall, this project helped me develop my skills in data visualization, analysis, and collaboration.
