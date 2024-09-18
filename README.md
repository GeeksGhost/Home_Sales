# Home Sales Data Analysis with Apache Spark

## Project Overview
This project demonstrates data analysis on a home sales dataset using Apache Spark SQL. The analysis involves calculating average home prices based on specific criteria such as the number of bedrooms, bathrooms, floors, and the size of the home. Additionally, we optimized the performance by caching and partitioning the data.

## Questions Answered

### 1. What is the average price for a four-bedroom house sold for each year?
For this question, the average price of houses with four bedrooms was calculated for each year. The result was rounded to two decimal places, providing insights into how prices have fluctuated over the years for homes with four bedrooms.

### 2. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
Here, we focused on homes with three bedrooms and three bathrooms. The average price was calculated for each year the home was built, allowing us to track price trends for these specific types of homes over time.

### 3. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
This query refined the criteria to include homes that not only have three bedrooms and three bathrooms but also have two floors and a living area of at least 2,000 square feet. The average price for these homes was calculated for each year of construction, providing a more focused analysis of higher-end homes.

### 4. What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?
In this analysis, homes were grouped by their "view" rating, and the average price for each group was calculated, provided the average price was at least $350,000. This query helps in understanding the correlation between a home’s view rating and its price. Additionally, the runtime of this query was recorded to evaluate performance.

## Environment Setup

To replicate this analysis, the following are required:
- **Apache Spark**
- **Python 3.x** (for PySpark usage)
- **Jupyter Notebook** or **Google Colab** for interactive work with SparkSQL

### Installation
1. Install Apache Spark (or use Google Colab, which offers built-in support for Spark).
2. Install required Python packages:
   ```bash
   pip install pyspark
