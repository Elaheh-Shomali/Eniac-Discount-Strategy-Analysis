# Eniac's Discount Strategy Analysis: Data Cleaning & Storytelling Project

## Summary
This project was conducted as part of my work as a Data Scientist at **Eniac**, an e-commerce tech company. The primary objective was to analyze internal, non-anonymized data to address a critical business debate: _Are discounts beneficial for the company in the long run?_ The stakeholders involved in this discussion had opposing perspectives:

- **Marketing Team Lead**: Believes discounts drive customer acquisition, satisfaction, and retention.
- **Board Investors**: Concerned about reduced revenue and prefer positioning the company in the quality segment.

To provide actionable insights, this project aimed to answer key questions about product categorization, pricing distribution, discount practices, and the impact of seasonality on sales. However, the dataset presented significant challenges, such as inconsistencies and corruption, which required extensive data cleaning and preprocessing. The analysis was conducted using Python to handle the complexity of tasks.

## Languages and Libraries Used
### Languages
- **Python**

### Libraries
- **Pandas**: For data cleaning and manipulation
- **NumPy**: For numerical computations
- **Matplotlib & Seaborn**: For data visualization
- **datetime**: For handling dates and analyzing seasonality

## Key Learnings
- **Data Quality Assessment**: Reinforced the importance of assessing data integrity before analysis.
- **Data Cleaning Techniques**: Gained experience in resolving inconsistencies, handling missing values, and standardizing formats.
- **Storytelling with Data**: Learned how to present findings to reconcile conflicting stakeholder viewpoints.
- **E-commerce Insights**: Improved understanding of pricing strategies and their implications for sales and revenue.

## Challenges Overcame
1. **Data Inconsistencies**: The dataset had issues such as missing values, duplicates, and incorrect formats. These were addressed through meticulous cleaning processes.
2. **Complex Relationships**: Working with multiple interconnected tables (orders, orderlines, products, brands) required careful handling of joins and aggregations.
3. **Balancing Stakeholder Expectations**: The project had to present findings neutrally, considering the opposing views of the Marketing team and the investors.
4. **Seasonality Analysis**: Extracting meaningful insights from seasonal sales patterns required detailed date handling and visualization techniques.

## Additional Reflections
Data cleaning is often considered a tedious part of data projects, but this experience highlighted its crucial role in building a foundation for trustable analysis. Addressing data corruption issues early ensured that subsequent analyses were reliable and meaningful.

Additionally, this project emphasized the need for effective communication with stakeholders. 

## Repository Structure

This repository is organized to ensure a clear and logical structure, facilitating ease of navigation and understanding of the project workflow. Below is an outline of the main components:

### 1. Notebooks
This folder contains Jupyter notebooks used throughout the project to analyze and process the datasets. Key scripts include:

- **1_data_cleaning**: Outlines the data cleaning steps required for preparing datasets. These steps are designed to handle inconsistencies, missing values, and other quality issues across new or existing datasets.

- **2_quality_assessment**: Evaluates the datasets against specific quality attributes such as completeness, consistency, and reliability. This ensures the data is suitable for analysis and decision-making.

- **3_category_creation**: Focuses on creating meaningful categorical variables from numerical data (e.g., product prices). These categories enhance the richness of the analysis by enabling slicing, filtering, and grouping of data.

- **4_analysis_business_questions**: Conducts a detailed analysis of the datasets to address the central business question: _Is offering discounts beneficial for the company?_ Insights from this notebook drive the strategic recommendations.

### 2. Output
This folder includes the presentation of key findings from the analysis. The output is designed to communicate insights effectively to stakeholders, balancing technical depth with actionable conclusions.

## Conclusion
This project demonstrated the power of data-driven decision-making, even when starting with chaotic and inconsistent datasets. By cleaning the data and answering key business questions, I helped shed light on Eniac’s discount strategy. While further exploration is necessary, the analysis provided a clearer understanding of the impact of discounts on sales, revenue, and customer behavior.

The insights gained not only addressed the current business debate but also set the stage for improved data collection practices and more refined future analyses. This project underscores the value of combining technical expertise with business acumen to drive meaningful outcomes.

