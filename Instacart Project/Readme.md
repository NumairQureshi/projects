Instacart Data Analysis and EDA (Exploratory Data Analysis)

link to the live project: https://nbviewer.org/github/NumairQureshi/projects/blob/main/Instacart%20Project/Instacart%20Project.html

Overview

This project is a comprehensive Exploratory Data Analysis (EDA) of a subset of the publicly available Instacart dataset, aimed at uncovering meaningful insights related to customer purchasing habits, product reordering behavior, and more. By utilizing various Python libraries such as pandas, matplotlib, and seaborn, this project walks through multiple stages, including data cleaning, missing value imputation, and insightful visualizations.

The dataset consists of five CSV files with data about customer orders, products, aisles, and departments. This analysis allows us to answer critical questions regarding customer behaviors, such as how frequently items are reordered, how long customers wait before reordering, and what products are frequently bought together.

Project Structure

The project contains the following files:
	1.	instacart_orders.csv: Contains the details of customer orders.
	2.	products.csv: Contains product details including names and IDs.
	3.	order_products.csv: Contains information about the individual items in each order.
	4.	aisles.csv: Contains aisle details in which products are categorized.
	5.	departments.csv: Contains department information for product categorization.
	6.	EDA_final_project_template.ipynb: Jupyter notebook that serves as the template for the analysis.

Key Features

This project aims to answer critical questions using pandas for data wrangling and matplotlib for visualizing insights:
	•	Data Cleaning: Identifying and fixing issues such as missing values and duplicates across the dataset.
	•	Customer Behavior Analysis: Insights into how often customers reorder items and the most popular products.
	•	Exploratory Data Analysis:
	•	Analyzing the distribution of orders placed at various hours of the day and days of the week.
	•	Identifying trends in order frequency and top-selling items.
	•	Assessing reorder behavior and customer loyalty.

Tasks Completed

The project is divided into the following sections:
	1.	Data Preprocessing:
	•	Merged relevant data to enrich the dataset (i.e., added user_id to order_products).
	•	Cleaned the data by filling missing values, handling duplicates, and ensuring correct data types.
	2.	Exploratory Data Analysis (EDA):
	•	Verified and validated column ranges such as order_hour_of_day and order_dow to ensure correctness.
	•	Created visualizations to show trends in customer orders (e.g., when people tend to shop, which products are frequently reordered, etc.).
	•	Analyzed the frequency of reorders and the number of items customers typically purchase in a single order.
	3.	Insights:
	•	Found that certain products like “Banana” and “Bag of Organic Bananas” are reordered frequently, indicating high customer loyalty to these items.
	•	Identified that the most frequent shopping hours are in the late morning and early afternoon.
	•	Discovered a wide range of customer ordering behaviors, with some users placing only a single order while others reorder multiple times.

Key Findings
	•	Top 20 Popular Products: Some products like “Banana” and “Organic Strawberries” appeared frequently in customers’ carts.
	•	Reorder Proportion: High reorder proportions were observed for popular products like “Organic Raspberries” and “Organic Hass Avocado,” indicating that these items are frequently purchased again.
	•	Time of Day and Day of Week Analysis: The majority of orders are placed during the day, with peak shopping occurring in the late morning and early afternoon.

How to Run the Project

To run this project locally, follow these steps:
	1.	Clone the repository:

git clone https://github.com/your-username/instacart-eda.git


	2.	Install required libraries:
Create a virtual environment and install the necessary libraries by running:

pip install -r requirements.txt


	3.	Run the Jupyter notebook:
Start the Jupyter notebook server and open EDA_final_project_template.ipynb:

jupyter notebook



Tools and Technologies Used
	•	Python 3.x
	•	pandas: For data manipulation and cleaning.
	•	matplotlib & seaborn: For visualizing the data and insights.
	•	Jupyter Notebook: For running the analysis and documenting the process.

Conclusion

This project demonstrates the ability to manipulate and analyze large datasets, uncovering useful insights regarding customer behavior. The analysis helps businesses understand shopping habits and optimize product stocking and promotional strategies. The project showcases how Exploratory Data Analysis (EDA) can drive actionable business insights in a data-driven environment.

Additional Resources
	•	Pandas Documentation
	•	Stack Overflow - Pandas Merging
