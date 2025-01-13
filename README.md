# Walmart_Sales_Data
![walmart_project-piplelines](https://github.com/user-attachments/assets/e36bfbce-4bd1-4f82-8b21-c577c4b42608)

  This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions. The project is ideal for data analysts looking to develop skills in data manipulation, SQL querying, and data pipeline creation.


# PROJECT STEPS 

### 1. Set Up the Environment
- Tools Used: Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)
- Goal: Create a structured workspace within VS Code and organize project folders for smooth development and data handling.

### 2. Set Up Kaggle API

- API Setup: Obtain your Kaggle API token from Kaggle by navigating to your profile settings and downloading the JSON file.
- Configure Kaggle:
Place the downloaded kaggle.json file in your local .kaggle folder.
Use the command kaggle datasets download -d <dataset-path> to pull datasets directly into your project.

### 3. DataSet
- Dataset Link: [Walmart Data](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)

### 4. SQl Connector Query

 `pip install pandas numpy sqlalchemy mysql-connector-python psycopg2`
  

### 5. Set Up Kaggle API

- Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
- Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
- Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
- Currency Formatting: Use .replace() to handle and format currency values for analysis.
- Validation: Check for any remaining inconsistencies and verify the cleaned data.

### 6. Buisness Query
1. Which branches generate the highest total sales?
2. What are the top 5 categories contributing the most to the total profit?
3. What are the most frequently used payment methods across branches?
4. Which transactions received the highest customer ratings?
5. How does total revenue vary day by day?
6. What are the busiest hours for sales across branches?
7. Which products/categories have the highest sales quantities?
8. How does profit margin change across months or seasons?
9. Which cities contribute the most to overall sales?
10. Does lowering unit price correlate with higher sales quantity?
