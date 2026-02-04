This README.md documentation is designed to accompany your Python project, explaining the methodology, technical choices, and analytical findings required by the project guidelines.

Project: Exploratory Analysis of Synthetic Customer Transaction Data
1. Project Overview
This project focuses on mastering fundamental data science workflows by simulating a real-world e-commerce environment. The core objective is to generate synthetic customer data, perform initial inspections and cleaning, and utilize statistical computation to tell a story through data visualization.

2. Technical Methodology
Data Generation (Task 1)
Using NumPy and Pandas, a dataset of 600 entries was programmatically generated to ensure a robust sample size. The dataset includes:

Numerical Features: Age (18-70), PurchaseAmount (simulated using a Gamma distribution), and LoyaltyPoints.

Categorical Feature: Region (North, South, East, West) to allow for segmented analysis.

Data Inspection & Cleaning (Task 2)
To maintain data integrity, the workflow includes:

Data Type Verification: Ensuring numerical and categorical fields are correctly assigned for analysis.

Missing Value Handling: Documenting the check for null values to ensure the dataset is complete and "clean".

Summary Statistics: Calculating the mean, median, standard deviation, and quartiles for all numerical columns to understand data distribution.

3. Data Visualization (Task 3)
The project utilizes three distinct plot types to explore the underlying data structure:

Histogram: Visualizes the distribution of PurchaseAmount to identify spending trends.

Box Plot: Compares a numerical variable (PurchaseAmount) across the categorical Region to identify variances and outliers.

Scatter Plot: Explores the relationship between Age and LoyaltyPoints to detect potential correlations.

4. Key Findings & Analysis (Task 4)
Based on the generated statistics and visualizations, the following insights were derived:

Central Tendency & Spread: The PurchaseAmount distribution is typically right-skewed, meaning while most customers spend a moderate amount, a select group of high-value transactions significantly influences the mean.

Regional Consistency: The Box Plot reveals whether spending habits are uniform across geographic regions or if specific areas show higher volatility or median spend.

Correlation: The Scatter Plot determines if a relationship exists between customer age and loyalty point accumulation, which is critical for targeted marketing.

5. Expected Deliverables
Python Code: Plain text implementation for data generation and plotting.

Statistical Table: Clear output of descriptive statistics for all numerical columns.


