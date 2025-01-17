# BIG-DATA-ANALYSIS

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: ARJUN BHAGAVAN LAGAD

**INTERN ID**: CT08HJY

**DOMAIN**: DATA ANALYSIS

**BATCH DURATION**: DECEMBER 30, 2024 TO JANUARY 30, 2025

**MENTOR NAME**: NEELA SANTHOSH

Internship Task 1: Analyzing Flipkart Big Billion Days Product Sale Dataset Using PySpark on Google Colab

For my first internship task, I undertook an extensive analysis of the Flipkart Big Billion Days product sale dataset. The dataset, sourced from GitHub, offers a wealth of information about product categories, pricing, discounts, ratings, and other key metrics, making it a suitable choice to showcase the power of PySpark for analyzing large datasets. The primary objective of this task was to demonstrate the scalability and efficiency of PySpark for processing and deriving insights from big data.

Dataset Overview

The Flipkart Big Billion Days dataset consists of diverse product categories and associated attributes like product names, categories, discounted prices, original prices, customer ratings, and reviews. These attributes provide an excellent opportunity to analyze customer buying behavior, product popularity, and the impact of discounts during one of the largest online sale events in India.

Environment and Tools Used

I utilized Google Colab for this analysis, a cloud-based platform that integrates seamlessly with PySpark and provides the computational resources required for handling large datasets. The integration of Google Colab with PySpark eliminated the need for a local Hadoop or Spark cluster, streamlining the development process. The combination of PySpark and Google Colab allowed me to focus solely on the analysis, leveraging the parallel processing capabilities of PySpark to manage the dataset efficiently.

Steps and Methodology

1. Data Ingestion
The first step was loading the dataset into Google Colab. Using PySpark’s DataFrame API, I imported the dataset from GitHub and explored its structure. PySpark’s capabilities in handling large data files in various formats (CSV, JSON, etc.) made the ingestion process straightforward and efficient.


2. Data Cleaning and Preprocessing
Data cleaning was an essential step, as the raw dataset contained missing values, duplicates, and inconsistencies. I utilized PySpark’s DataFrame operations to handle these issues, such as removing duplicates, filling null values, and converting data types to ensure consistency. This preprocessing step ensured the data was ready for meaningful analysis.


3. Exploratory Data Analysis (EDA)
Using PySpark, I conducted an in-depth exploratory data analysis to uncover patterns and trends. Key insights from this step included:

Identifying the most popular product categories during the Big Billion Days sale.

Analyzing the average discount percentage across categories to determine which categories offered the highest savings.

Studying the relationship between customer ratings and the discount percentage to understand if deeper discounts correlated with higher ratings.



4. Advanced Analysis and Visualization
I implemented advanced data analysis techniques to derive actionable insights. For example, using PySpark’s SQL module, I queried the dataset to identify high-performing products and underperforming categories. Additionally, I created visualizations in Google Colab using Matplotlib and Seaborn to complement the analytical results. These visualizations included bar graphs, heatmaps, and scatter plots, which highlighted sales trends and customer preferences.


5. Scalability Demonstration
One of the key objectives was to demonstrate PySpark's scalability. By leveraging PySpark’s distributed computing capabilities, I processed the dataset significantly faster than traditional methods. This step underscored the advantages of using PySpark for large-scale data analysis tasks.



Outcomes and Insights

The analysis provided valuable insights into customer buying behavior during the Flipkart Big Billion Days sale. Some key takeaways included:

Electronics and fashion products emerged as the top-selling categories.

Products with discounts in the range of 40-60% received the highest customer ratings.

A significant correlation was observed between product ratings and sales volume.


Conclusion

This internship task was an excellent opportunity to explore PySpark’s capabilities for big data analysis. By leveraging the Flipkart Big Billion Days dataset, I demonstrated my ability to clean, process, analyze, and visualize large datasets efficiently. Using Google Colab as the development environment simplified the integration with PySpark and provided the necessary computational resources. This task not only honed my technical skills but also deepened my understanding of customer behavior and sales trends, laying a strong foundation for my career in data analysis and data science
