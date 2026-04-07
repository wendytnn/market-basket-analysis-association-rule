# Market Basket Analysis: Association Rule Mining for Groceries

## Project Overview
This project implements **Association Rule Mining** (Market Basket Analysis) on a retail grocery dataset. The primary goal is to discover hidden patterns and relationships between products purchased by customers. By leveraging data mining techniques, the project identifies frequent itemsets and generates actionable rules that can inform retail strategies like product placement, inventory management, and promotional bundling.

## Dataset
- **Name:** `GroceriesDatasetv1.csv`
- **Description:** The dataset contains historical transaction records, including customer IDs, order IDs, and item descriptions.
- **Key Characteristics:** - Covers transactions over multiple years (e.g., 2023–2024).
    - Features unique product categories ranging from dairy to household items.

## Features & Workflow
The analysis is structured into several key phases:

1.  **Data Preprocessing & Cleaning**:
    - Handling missing values and ensuring data integrity.
    - Formatting date columns and standardizing item descriptions.
    - Grouping transactions by `Order_ID` to create a "basket" format.
2.  **Exploratory Data Analysis (EDA)**:
    - Visualizing top-selling products (e.g., Whole Milk, Rolls/Buns, Vegetables).
    - Analyzing transaction trends over time (monthly and yearly).
    - Customer behavior profiling (average items per basket, frequency of visits).
3.  **Association Rule Mining**:
    - Implementation of the **Apriori Algorithm** to find frequent itemsets.
    - Generation of rules based on metrics: **Support**, **Confidence**, and **Lift**.
    - Filtering and sorting rules to identify the most significant "Strong Rules."
4.  **Advanced Analysis**:
    - Multi-itemset analysis (up to 4-itemsets).
    - Year-specific analysis (e.g., focus on 2024 trends).
    - Visualization of rules using heatmaps or scatter plots.

## Tools & Libraries
- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and numerical analysis.
- **Matplotlib & Seaborn**: Data visualization and plotting.
- **MLxtend**: Used for the Apriori algorithm and association rule generation.
- **Tabulate**: Used for clean, readable console output of data frames.

## Key Insights
- **Core Product Affinities**: Identified which items (e.g., yogurt and milk) are frequently bought together, suggesting logical aisle pairings.
- **Trend Identification**: Observed seasonal spikes in shopping behavior and categorized products into high-frequency vs. niche categories.
- **Strategic Recommendations**: Provided data-driven suggestions for cross-selling and optimizing store layouts.

## How to Use
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/grocery-association-rules.git](https://github.com/your-username/grocery-association-rules.git)