# QlikSense Dashboard
Done by: Ng Chuen Siong, Nelson

## Objective
Build a dashboard to track a company’s product sales, profitability, and quantity ordered. <br>

## Procedure
<b>Datasets</b><br>
The main dataset is sourced from Kaggle<a href="https://www.kaggle.com/datasets/beekiran/sales-data-analysis"><sup>1</sup></a>, supplemented by additional self-generated datasets to demonstrate drill-down and rollup functions on QlikSense. <br>

Refer to csv files within input_data.<br>

<b>Data Engineering</b><br>
First, design the star schema for the project (see Data Model - Star Schema.pdf). Next, divide the main dataset into fact and dimension tables. Then, enrich the respective dimension tables with the self-generated datasets. Refer to ‘Data Engineering.ipynb’ for the data engineering work done. <br>

Refer to csv files within star_schema_data.<br>

<b>Dashboard Design</b><br>
Perform wireframing for the dashboard to visualize the layout and components on a piece of paper.<br>

<b>Build QlikSense Dashboard</b><br>
Load the fact and dimension tables into QlikSense, and join them using associative joins to form the data model. Develop the dashboard based on the wireframe as a reference. Conduct data quality checks to ensure accuracy. <br>

## Operate QlikSense Dashboard
Upload the csv files within star_schema_data and Sales Performance Dashboard.qvf to QlikSense.<br>

Refer to Sales Performance Dashboard - pg 1.pdf and Sales Performance Dashboard - pg 1.pdf for QlikSense Dashboard design.
