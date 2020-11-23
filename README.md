# Data-Analysis-and-Visualization-with-Python

# Project Objective

This project aims at performing Data Analysis and Visualization of each feature and understand if they have any effect on job placement/salary. We analyze and plot each feature. Also, further analysis is necessary to substantiate the conclusions arrived in this project.  

# Data Source

The dataset hereby used was extracted from https://www.kaggle.com/ The direct link of the "Placement_data_Full_Class" can be accessed via https://www.kaggle.com/benroshan/factors-affecting-campus-placement

# List of Libraries used in the project

1. Pandas
2. Numpy
3. Maptplotlib.pyplot
4. Seaborn

# Exploratory Data Analysis
We explored the entire dataset with respect to columns and rows. The dataset contains 15 different variables and 215 observations. Most of the variables are coded in very unique manner and we described them in this step:

sl_no = Serial Number

ssc_p = Secondary Education Percentage - 10th Grade

ssc_b = Borard of Education- Central/Others

hsc_p = Higher Secondary Education percentage - 12th Grade

hsc_b = Board of Education - Central/Others

hsc_s = Specialization in Higher Secondary Education

degree_p = Degree Percentage

degree_t = Under Graduation(Degree type)- Field of degree education

workex = Work Experience 

mba_p = MBA percentage

etest_p = Employability test percentage (conducted by college)

# Data Cleaning

One of the variables in the dataset (sl_no) is irrelevant to our analysis since it is the serial number for each observation. We proceeded to drop it.

# Data Visualization
We performed different data visualizations for features based on the type of the variable. 
For the most part we perfomed Countplots, Boxplots and Lineplots.
![](https://github.com/vimpicode/Data-Analysis-and-Visualization-with-Python/blob/main/1%20Gender%20Count%20Plot.png)

# Conclusion
The conclusions arrived from each of the plots, could significantly change if we apply the same dataset in regression model such as Multilinear Regression. However, that can be done in another project since it is not the scope of this one. Also, analysing one feature at a time gives us a limited and skewed understanding of the explanatory power of each feature. For further projects we can also conduct additional analysis of the descriptive statistics for all features.

# References List

The following documentations and resources were used during this project:

1. Data Source is from Kaggle: https://www.kaggle.com/benroshan/factors-affecting-campus-placement

2. Seaborn 0.11.0 Documentation guide: https://seaborn.pydata.org/generated/seaborn.pairplot.html 

3. Data Analysis with Python (Youtube Toturial Video) https://www.youtube.com/watch?v=r-uOLxNrNk8&t=6102s

4. Pythod documentation tutorial: https://docs.python.org/3/tutorial/index.html


