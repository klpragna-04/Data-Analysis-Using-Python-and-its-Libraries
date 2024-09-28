# Amazon Sales Data Analysis

This repository contains a data analysis project using Python, focused on exploring and understanding sales data from Amazon. The project involves cleaning the dataset, performing exploratory data analysis (EDA), and visualizing key trends and insights using popular data manipulation and visualization libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## Project Overview

The goal of this project is to analyze Amazon's product sales data to derive meaningful insights about product performance, discounts, and customer ratings. We perform tasks such as:

- Data cleaning and preprocessing
- Handling missing values
- Renaming columns for better readability
- Data transformation (e.g., converting prices to numerical format)
- Exploratory Data Analysis (EDA) through visualizations
- Understanding category-wise sales and ratings distribution

## Dataset

The dataset used in this project is a CSV file (`amazon.csv`) containing information such as:
- Product name
- Product category
- Discounted price
- Actual price
- Discount percentage
- Rating count

## Key Insights

### 1. **Top-selling Categories:**
   We observed that the majority of sales occur in categories such as **television** and **smartphones**. These categories show the highest total discounted price.

### 2. **Top-rated Products:**
   Analysis of customer reviews shows that **Amazon Basics Ethernet cables** receive the most reviews, highlighting their cost-effectiveness and quality. This indicates a potential area for increased focus on manufacturing more such products.

### 3. **Correlation Analysis:**
   We used a heatmap to visualize the correlation between various factors such as discount percentage, actual price, discounted price, and rating count.

## Tools & Libraries Used

- **Python**: The primary programming language for this project.
- **Pandas**: Used for data manipulation and cleaning.
- **NumPy**: Used for numerical operations.
- **Matplotlib**: Used for basic plotting and visualizations.
- **Seaborn**: Used for creating more advanced visualizations.
- **Jupyter Notebook**: For writing and documenting the analysis.

## Exploratory Data Analysis (EDA)

The following steps were taken during EDA:

1. **Data Cleaning**: Handling missing values and formatting prices.
2. **Category-wise Sales Analysis**: Grouping sales data by category to identify top-performing categories.
3. **Product-wise Rating Analysis**: Sorting products by customer ratings to highlight the most reviewed products.
4. **Correlation Analysis**: Using a heatmap to understand the relationships between different variables such as price and ratings.

## Future Improvements

- Analyze customer review text to perform sentiment analysis.
- Incorporate time-series data to observe seasonal trends in product sales.

## Conclusion

Through this analysis, we've identified key insights regarding Amazon product sales, particularly in terms of pricing, discounts, and customer satisfaction. This project demonstrates how data can be effectively used to drive business decisions.

## How to Use

1. Clone this repository:
   ```
   git clone https://github.com/your_username/amazon-sales-analysis.git
   ```
2. Install the necessary libraries:
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to explore the data and visualizations.

---

