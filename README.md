# Diwali Sales Data Analysis 🛍️

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on Diwali sales data to improve customer experience and drive business growth. By analyzing various consumer attributes and purchasing patterns, we identify the most profitable customer segments and product categories.

## Objectives
*   Identify the demographics (age, gender, state) with the highest purchasing power.
*   Find the top-performing product categories.
*   Determine the impact of marital status and occupation on sales.
*   Provide actionable insights for targeted marketing campaigns during festive seasons.

## Dataset
The dataset used is `Diwali Sales Data.csv`. It contains roughly 11,000+ entries with 15 columns, including:
*   **User_ID**: Unique identifier for customers.
*   **Cust_name**: Name of the customer.
*   **Product_ID**: Unique identifier for products.
*   **Gender**: M/F.
*   **Age Group**: Categorized age brackets.
*   **State & Zone**: Geographical data.
*   **Occupation**: Industry/Field of work.
*   **Orders**: Number of orders placed.
*   **Amount**: Total sales value.

## Key Insights
*   **Gender**: Females are the primary buyers and contribute significantly more to the total sales amount compared to males.
*   **Age**: The 26-35 age group is the most active consumer segment.
*   **Geography**: Uttar Pradesh, Maharashtra, and Karnataka are the top states in terms of both order count and total revenue.
*   **Occupation**: Professionals in IT, Healthcare, and Aviation sectors show the highest spending capacity.
*   **Products**: Food, Clothing, and Electronics are the most sold categories.

## Technologies Used
*   **Python**: Core programming language.
*   **Pandas**: Data manipulation and cleaning.
*   **NumPy**: Numerical operations.
*   **Matplotlib / Seaborn**: Data visualization.
*   **Jupyter Notebook**: Interactive environment for analysis.

## Project Structure
1.  **Data Cleaning**: Removed null values and dropped unnecessary columns (`Status`, `unnamed1`).
2.  **Data Processing**: Corrected data types (e.g., float to int for `Amount`).
3.  **Visual Exploration**: Used Bar charts, Count plots, and GroupBy aggregations to visualize trends.

## How to Run
1. Clone this repository.
2. Ensure you have Python installed.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
