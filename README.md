# Diwali Sales Analysis

## Project Overview

This project analyzes Diwali sales data to identify trends and insights related to customer demographics and purchasing behavior. The focus is on understanding how factors like age, gender, state, marital status, occupation, product category, and product ID influence buying patterns during Diwali.

## Project Learnings 
Performed data cleaning and manipulation Performed exploratory data analysis (EDA) using pandas, matplotlib and seaborn libraries Improved customer experience by identifying potential customers across different states, occupation, gender and age groups Improved sales by identifying most selling product categories and products, which can help to plan inventory and hernce meet the demands

## Procedure Followed :

## Data Cleaning

To prepare the data for analysis, the following steps were taken:
- **Dropped Unrelated Columns:** Removed columns such as `Status` and `unnamed1` that were not relevant to the analysis.
- **Handled Missing Values:** Dropped rows with null values to ensure the integrity of the dataset.

```python
df.drop(['Status', 'unnamed1'], axis=1, inplace=True)   # Drop unrelated columns
df.dropna(inplace=True)  # Drop rows with null values
```

## Exploratory Data Analysis (EDA)

The EDA was conducted to explore the relationship between various demographic factors and sales behavior. The key variables analyzed include:
- **Age**
- **Gender**
- **State**
- **Marital Status**
- **Occupation**
- **Product Category**
- **Product ID**

### Key Insights

- **Demographic Target:** Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka.
- **Occupational Influence:** The most active buyers work in IT, Healthcare, and Aviation industries.
- **Product Preferences:** These buyers predominantly purchase products in the Food, Clothing, and Electronics categories.

## Conclusion

The analysis suggests a clear trend in Diwali sales, where certain demographic groups are more likely to purchase specific categories of products. This information can be leveraged for targeted marketing strategies during the Diwali season.

## Technologies Used

- **Python:** For data cleaning, manipulation, and analysis.
- **Pandas:** For data handling and preprocessing.
- **Matplotlib & Seaborn:** For data visualization.
- **Power BI:** For interactive visualizations and dashboards (optional if used).


## Future Work

- Extend the analysis to include more variables such as income level or educational background.
- Build predictive models to forecast future sales trends.
- Integrate the analysis with real-time sales data for dynamic insights.
