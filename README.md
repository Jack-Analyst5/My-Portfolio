# Jack delos Reyes - Data Analyst Portfolio
## About

Hi, I'm Jack! I’m a teacher by profession with over 15 years of experience in education and data management, now transitioning into a career in Data Analytics. Through my recent training, I’ve developed strong skills in SQL, Excel, Power BI and Python, along with hands-on experience in data cleaning, analysis, and visualisation. 

I decided to enroll with Mission Ready HQ to deepen my knowledge in data analytics, where I gained practical experience working with large datasets (5K–85K+ records), building dashboards, performing KPI reporting, and uncovering insights to support data-driven decision-making. 

I’m passionate about using data to solve real-world problems and continuously improving my analytical skills. This repository showcases my skills, shares part of my projects, and tracks my progress in Data Analytics / Data Science related topics.

My CV is available in [PDF](https://github.com/Jack-Analyst5/CV/blob/main/CV_Jack_delos_Reyes.pdf)


## TABLE OF CONTENTS
- [About](https://github.com/Jack-Analyst5/CV/blob/main/README.md#about)
  
- [Project Task](https://github.com/Jack-Analyst5/PROJECT-TASKS-)
  - [Introduction](https://github.com/Jack-Analyst5/PROJECT-TASKS)
  - [Python](https://github.com/Jack-Analyst5/First-time/blob/main/Python)
    --[Exploratory Data Analysis](https://github.com/Jack-Analyst5/Exploratory-Data-Analysis/blob/main/Mission%203_%20Exploratory%20Data%20Analysis%20(EDA)%20with%20the%20Sales%20Dataset%20using%20Pandas%20and%20d%20Matplotlib_Seaborn%20(2).ipynb)
    --[Machine Learning](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models)
    --[Predictive Analytic Models](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models/blob/main/Mission%205%20(2).ipynb)
  - [SQL](https://github.com/Jack-Analyst5/SQL)
  - [Power BI](https://github.com/Jack-Analyst5/Power-BI)
 - [Internship](https://github.com/Jack-Analyst5/Internship/issues/1)

---

---

# [PROJECT-TASKS](https://github.com/Jack-Analyst5/PROJECT-TASKS)
# [Introduction](https://github.com/Jack-Analyst5/PROJECT-TASKS)

This repository showcases my work outputs developed using Microsoft Fabric Notebooks during my studies at Mission Ready.
The projects demonstrate my hands-on experience in data analysis, including data cleaning, exploration, and visualisation. Some project includes a overview of the project, its objectives or goal, scope, and key outcomes to provide a clear understanding of the work.

In addition, I have included screenshots from other tasks completed during my time at Mission Ready to highlight my broader exposure and practical application of data tools and techniques.
Through this work, I have built a strong foundation in working with real-world datasets, identifying trends, and delivering clear, data-driven insights. These projects reflect my ongoing growth and commitment to developing as a Data Analyst.

# [Python](https://github.com/Jack-Analyst5/First-time/blob/main/Python)
## [Exploratory Data Analysis](https://github.com/Jack-Analyst5/Exploratory-Data-Analysis/blob/main/Python%20-%20EDA%20(2).ipynb)
## Project Overview
This project is part of my journey in learning Python. 
This notebook demonstrates the use of Python, Pandas, Matplotlib, and Seaborn to perform Exploratory Data Analysis (EDA) on a retail sales dataset. The dataset contains transactional information from a retail business, including sales, invoices, products, stores, countries, quantities sold, and pricing details. The purpose of the analysis is to clean the data, understand its structure, identify trends, and generate insights through statistical analysis and visualizations.

The analysis begins with data quality checks, where the Sales DataFrame is examined for missing values. Any missing (NaN) values found in the Sales and UnitPrice columns are replaced with zero to ensure consistency and prevent errors during analysis. Basic descriptive statistics are then calculated for the Quantity and UnitPrice columns, providing key measures such as count, mean, minimum, maximum, and standard deviation. This helps understand the overall distribution and variability of sales transactions.

The notebook then uses data visualization techniques to explore patterns within the data. A scatter plot is created to examine the relationship between Quantity Sold and Sales Revenue, helping identify whether higher quantities lead to increased sales. A histogram is used to visualize the distribution of the Sales values and identify common sales ranges, outliers, or skewness in the data. A line chart is also developed to show sales trends over time, allowing users to observe seasonal patterns, peaks, and declines in business performance.
In addition to visual analysis, the notebook performs grouping and aggregation operations using Pandas. Sales data is grouped by Product Category to calculate total sales for each category, enabling the identification of top-performing product groups. A pivot table is then created to summarize sales by Country and Product Category, providing a multi-dimensional view of sales performance across different markets and product segments.

Overall, this notebook applies fundamental data analysis techniques to transform raw retail transaction data into meaningful business insights. It demonstrates how Python and Pandas can be used for data cleaning and summarization, while Matplotlib and Seaborn help visualize trends and patterns that support decision-making and business performance analysis.

## Goal
Application of Python for basic operations, Pandas for data manipulation, and Matplotlib/Seaborn for visualizations. 

## Dataset
The dataset represents transaction data from a retail business, specifically sales data for products sold in various stores. 

## Tasks included: 
Merging DataFrames
Exploratory Data Analysis (EDA)- Conduct EDA by analysing the data, identifying patterns, trends, and outliers.
Data Visualisation – Scatter Plot, Histogram, and Line Chart
Correlation and Data Insights 
Grouping and Aggregating

## Technologies
Python
Pandas
Matplotlib
Seaborn
Microsoft Fabric
Results

Using Python and EDA techniques, I explored relationships between variables and identified key factors that influence outcomes. Visualizations helped highlight trends, correlations, and patterns within the dataset.

# [Machine Learning:Regression Models](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models)

 [House Price Prediction: MLR vs Random Forest](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models/blob/main/Mission%204_%20Predicting%20House%20Price%20with%20Multiple%20Linear%20Regression%20%20(5).ipynb)

## Overview

This project compares the performance of two regression models, Multiple Linear Regression (MLR) and Random Forest (RF), in predicting house prices. The aim is to determine which model produces more accurate predictions based on the dataset.

---

## Goal

The study involves building predictive models using Multiple Linear Regression (MLR) and Random Forest (RF) techniques. The performance of these models is then evaluated using Root Mean Squared Error (RMSE) as the main metric. After assessing each model, their accuracy levels are compared to determine which performs better. Finally, different methods and approaches are identified to further improve overall model performance.

---

## Methodology

The methodology involves training two models, Multiple Linear Regression (MLR) and Random Forest (RF), to make predictions. Their performance is evaluated using Root Mean Squared Error (RMSE) and by visually comparing predicted values with actual values.


## Results
Through this project, I explored different modelling approaches to better understand how well they could capture patterns within the data. Both models were able to generate predictions that aligned reasonably well with actual outcomes, demonstrating their ability to learn from the dataset.
However, one model stood out with more consistent and reliable predictions. Its results were closer to the expected trend, which suggests that it was more effective in capturing the underlying relationships in the data. This comparison allowed me to see firsthand how different approaches can produce varying levels of accuracy, even when working with the same dataset.
Overall, the results gave me valuable insight into how model selection impacts performance and how important it is to evaluate models beyond just surface-level outcomes.

## Conclusion
This project reinforced the importance of experimenting with different analytical approaches to better understand data and improve predictive performance. While both models showed potential, the differences in their results highlighted how the structure of the data can influence which method performs best.
From a learning perspective, this experience helped me appreciate the full process of building and evaluating models—from preparing the data to interpreting the results. It also showed me that achieving better outcomes often requires continuous refinement, such as improving data quality, selecting meaningful features, and tuning models carefully.
Overall, this project was a valuable step in my development as a Data Analyst. It strengthened not only my technical skills, but also my ability to think critically about data, assess model performance, and communicate insights in a clear and meaningful way.

---

[Predictive Analytic Models](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models/blob/main/Mission%205%20(2).ipynb)

## Overview
This project presents a credit risk modelling initiative focused on classifying loan applications into approved (low-risk) and defaulted (high-risk) categories using machine learning techniques.

## Goal
The objective is to predict loan status from borrower data, using a binary classification approach where Class 0 represents low-risk loans and Class 1 represents high-risk loans; the dataset contains approximately 45,000 records with a 22% class imbalance toward high-risk cases.

## Methodology
The analysis uses borrower demographics, financial leverage, and credit history data, with exploratory analysis showing an average loan amount of $9,583, a mean interest rate of 11.0%, right-skewed loan distributions, and normally distributed credit scores; feature correlations highlight loan-to-income ratio and interest rate as key predictors, and three models—Logistic Regression, Gradient Boosting, and Random Forest—were evaluated.

## Results
Random Forest achieved the best performance with 92.87% accuracy, outperforming other models and delivering strong precision, recall, and F1-scores, with a confusion matrix showing high true negatives (6,797) and true positives (1,561), along with relatively low false positives (193) and false negatives (449).

## Conclusion
The model effectively predicts loan risk with high accuracy, supporting loss prevention through strong recall and ensuring fair approvals through high precision, providing a solid foundation for data-driven lending decisions and automated loan evaluation systems.



# [SQL](https://github.com/Jack-Analyst5/SQL/edit/main/README.md)
These are sample codes did for the course under this topic.

## Overview: 

These are some examples of my SQL tasks that I needed to do during the course. I worked on creating a structured data warehouse schema using the RetailStarSchema, where I defined several dimension tables such as ProductDimensionTable, CustomerDimensionTable, TimeDimensionTable, and PromotionDimensionTable. Each table was designed with appropriate attributes and primary keys to organize data effectively, while the SalesFactTable was created to store measurable data like revenue and units sold, linking all dimension tables through foreign keys. This setup demonstrates my understanding of star schema design and relational database principles. In addition to database design, I also performed analytical queries, such as calculating total revenue generated by each product and analyzing revenue contributions across different regions using joins, aggregations, and grouping techniques. These tasks highlight my ability to both design databases and extract meaningful business insights using SQL.


## SQL Tasks

Here are some examples of SQL queries and schema designs I created:


![Schema Design 1](https://github.com/Jack-Analyst5/SQL/blob/main/sql1.png)
![Schema Design 2](https://github.com/Jack-Analyst5/SQL/blob/main/sql2.png)
![Schema Design 3](https://github.com/Jack-Analyst5/SQL/blob/main/sql3.png)


# [Power BI](https://github.com/Jack-Analyst5/Power-BI)
Power BI TASK

# Overview
The project focuses on analyzing the sales performance of an international online retail company using datasets stored in an Azure SQL database. The project combined a primary dataset consisting of Date, Product, Invoice, and Sales tables with a secondary customer insights dataset containing demographic information such as age, gender, and product category preferences. Using Power BI, the team performed data cleaning, modeling, visualization, and advanced analytics to uncover key business trends and generate actionable insights. The analysis aimed to evaluate historical sales performance, understand customer behavior, identify revenue drivers, and assess areas of risk affecting business growth. Through interactive dashboards and reports, the team transformed raw data into meaningful business intelligence to support strategic decision-making.

# Objective 
The primary objective of this project was to analyze the company's sales and customer data to identify trends, opportunities, and challenges impacting business performance. The analysis sought to understand historical sales patterns, evaluate product and category performance, assess customer demographics and geographic distribution, and determine the causes of the current decline in sales. Additionally, a secondary retail customer insights dataset was incorporated to validate findings and provide deeper context regarding customer purchasing behavior. The ultimate goal was to leverage data-driven insights and Power BI visualizations to develop strategic recommendations that would help the company improve sales performance, reduce business risks, and achieve sustainable growth.

# Methodology
The team collected data from Azure SQL and an external retail dataset, then cleaned, transformed, and modeled the data in Power BI. Various analytical techniques, including sales trend analysis, customer segmentation, product performance evaluation, and forecasting, were used to generate insights and create interactive dashboards.

# Results
Financial and Sales Performance
The company generated approximately $1.19 million in sales between 2015 and 2018, with 2016 contributing $593,000, making it the strongest performing year. Sales showed clear seasonal peaks during the mid-year period (June–August) and holiday season (September–November).

# Product Performance
Product Performance
Uncategorized products and Christmas-related products generated the highest sales. The Christmas Retrospot Star Wood was identified as the top-performing product across all years, making it a significant contributor to revenue but also creating dependency on a seasonal item.

# Customer Insights
Customer activity was heavily concentrated in the United Kingdom, which accounted for 93% of customers. Germany, France, New Zealand, and Belgium represented much smaller customer segments, indicating a high dependence on a single market.

Secondary Dataset Findings
The secondary dataset revealed that 51.06% of customers were female, while middle-aged consumers were the most frequent purchasers. It also showed that beauty products were more popular among middle-aged shoppers, while older customers spent more on electronics.

# Year-To-Date (YTD) Analysis
The company experienced a 6.06% decline in YTD sales, resulting in a revenue shortfall of $27,665.86. The decline appears to be caused by overreliance on a seasonal top-selling product, concentration of revenue within a few categories, and heavy dependence on the UK market.

# Conclusion
Although the company achieved strong historical sales performance, the current sales decline highlights significant business risks. Without intervention, annual sales are expected to finish 6%–7.5% below the previous year. To improve performance, the company should diversify its products, strengthen customer retention in the UK, expand into new markets, and use demographic insights to better target high-value customer segments.

# Dashboard

![Overall Sales Analysis](PowerBI_1.png)

![Sales Performance from 2015-2018](PowerBI_2.png)

![Customer Insights](PowerBI_3.png)

![Year-to-Date Analysis](PowerBI_4.png)

![Forecast](PowerBI_5.png)





