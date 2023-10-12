# Exploratory-Data-Analysis-using-Python-and-Pandas
![logo](https://github.com/shirinshaik/Exploratory-Data-Analysis-using-Python-and-Pandas/assets/113626760/a9dee0f1-e548-4752-b656-94bc2d2ffba0)

## Objective

This project focuses on applying practical Exploratory Data Analysis (EDA) techniques on tabular datasets using Python packages such as Pandas and Numpy. The primary objectives are to produce data visualizations using Seaborn and Matplotlib, as well as to identify and handle duplicate and missing data.

## Introduction
In this project, we dive into the world of supermarket sales data to gain insights and valuable information through data analysis techniques.

Exploratory data analysis (EDA) is an especially important activity in the routine of a data analyst or scientist.It enables an in depth understanding of the dataset, define or discard hypotheses and create predictive models on a solid basis.

It uses data manipulation techniques and several statistical tools to describe and understand the relationship between variables and how these can impact business.

In fact, it’s thanks to EDA that we can ask ourselves meaningful questions that can impact business.

## Features
- Initial Data Exploration
- Univariate Analysis
- Bivariate Analysis
- Dealing With Duplicate Rows and Missing Values
- Correlation Analysis

## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Usage
The project is divided into tasks, each focusing on a specific aspect of exploratory data analysis. Here's a brief overview of the tasks:
### Task 1: Initial Data Exploration

Task 1 involves the crucial step of familiarizing ourselves with the dataset. We begin by setting up a Jupyter notebook environment and importing essential libraries like Pandas, Numpy, Seaborn, Matplotlib, and more. This lays the foundation for our exploratory data analysis.

The first major step is to read in the data and gain an initial understanding by examining the first few rows. We also take the opportunity to calculate some quick summary statistics to get an overview of the numeric columns.

Additionally, we investigate data types to ensure they are appropriately assigned. This includes converting the 'Date' column to a datetime format for consistency and analytical accuracy. We also set the date column as the index, facilitating time-based analysis.

This task serves as the gateway to a comprehensive exploration of the dataset.
### Task 2: Univariate Analysis

In this task, we dive into the univariate analysis of the dataset. Univariate analysis focuses on examining the characteristics of a single variable at a time. We explore both continuous and categorical variables separately to understand their distributions and summary statistics.

For continuous variables, we use tools like histograms and descriptive statistics to gain insights into their central tendencies, dispersions, and shapes of the distributions. This helps us identify any potential outliers or unusual patterns.

For categorical variables, we create bar plots to visualize the frequency distribution of each category. This allows us to observe the distribution of different categories within the dataset.

### Task 3: Bivariate Analysis

Task 3 revolves around bivariate analysis, where we explore the relationships between pairs of variables. This analysis is crucial for understanding how two variables interact with each other and if there are any patterns or correlations between them.

One aspect of bivariate analysis involves creating scatter plots and regression plots to visualize the relationship between customer ratings and gross income. This helps us determine if there is any linear association between the two variables.

Additionally, we use box plots to compare aggregate sales figures between different branches of supermarkets. This enables us to identify any significant variations in sales performance across branches.

We also examine sales patterns based on gender, providing insights into potential differences in purchasing behavior between men and women.

### Task 4: Dealing With Duplicate Rows and Missing Values

In Task 4, we focus on data cleaning by addressing duplicate rows and missing values. Duplicate rows can distort our analysis, so we identify and remove them to ensure the integrity of our dataset.

Next, we tackle missing values, a common issue in real-world datasets. Instead of simply deleting rows with missing values, we take a more strategic approach. For numeric columns, we replace missing values with the mean of their respective columns. For categorical columns, we use the mode to fill in missing values.

Additionally, we leverage the power of Pandas Profiler to automate parts of the exploratory data analysis, streamlining the data cleaning process.

### Task 5: Correlation Analysis

The final task, Task 5, involves correlation analysis. Here, we delve into the numeric variables in our dataset to understand their relationships.

We employ Numpy to calculate correlation coefficients between pairs of numeric variables. This provides us with a numerical indicator of how strongly two variables are related.

Furthermore, we generate a correlation matrix using Pandas, which displays all pairwise correlations between the numeric variables in our dataset. This matrix offers a comprehensive overview of the relationships within the data.

To enhance interpretability, we use Seaborn to visualize the correlation matrix as a heatmap. This allows us to quickly identify patterns and dependencies among variables.

## Notable Insights
- Uniform distribution in customer ratings.
- Ewallet as the most popular payment method.
- No strong relationship between customer ratings and gross income.

## Conclusion
In this project, I embarked on a comprehensive journey of Exploratory Data Analysis (EDA) utilizing Python and an array of powerful libraries. My primary objectives were to gain valuable insights from a supermarket sales dataset and apply practical EDA techniques.

Through a structured approach, I accomplished the following:

- INITIAL DATA EXPLORATION : I set up the environment, imported essential libraries, and gained an initial understanding of the dataset. This involved reading the data, viewing the first few rows, and performing basic summary statistics.
- UNIVARIATE ANALYSIS : I delved into individual variables, both continuous and categorical, to discern their distributions and characteristics. This provided crucial insights into the nature of each variable.
- BIVARIATE ANALYSIS : By exploring the relationships between pairs of variables, I unearthed potential correlations and patterns. This included assessing the connection between customer ratings and gross income, as well as scrutinizing sales performance across different branches.
- DEALING WITH DUPLICATE ROWS AND MISSING VALUES : I identified and handled duplicate rows and missing data, ensuring the integrity of my analysis. This step was pivotal in ensuring the accuracy and reliability of my findings.
- CORRELATION ANALYSIS : I quantified the relationships between numeric variables, uncovering potential dependencies within the dataset. This offered valuable insights into how different aspects of the data interact.

Additionally, I utilized Pandas Profiler for automated exploratory data analysis, streamlining my process.

★ This project not only enhanced my proficiency in Python and data analysis but also equipped me with a practical toolkit for approaching real-world datasets. The skills acquired are transferrable and can be applied to a diverse range of analytical endeavors.

★ Exploratory Data Analysis serves as a foundational step in any data-driven project, providing the bedrock for more complex analyses and actionable insights. With the knowledge gained from this project, I am well-equipped to tackle a wide array of data challenges and derive meaningful conclusions from diverse datasets.
