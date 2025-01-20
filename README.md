# Fetch_Take_Home_Assessment
## Overview
This repository contains datasets, Python notebooks, and SQL queries for data analysis and visualization related to a series of questions in a take-home assessment. The main components of the repository are as follows:

- Cleaned Datasets (ZIP file): The datasets for users, transactions, and products have been cleaned and processed. These datasets are packaged into a zip file for easy access.

- Python Notebook - Data_Quality_check_&_transform.ipynb: This notebook contains the Python code used to clean and transform the datasets. It covers tasks such as handling missing values, removing duplicates, standardizing data types, and ensuring that the datasets are properly formatted for analysis.

- Python Notebook - SQL.ipynb: This notebook contains the SQL queries used to answer both closed-ended and open-ended questions posed in the assessment. The queries were executed using SQLite, as an alternative to working with MySQL servers due to some technical limitations.

- Python Notebook - Visualizations.ipynb: This notebook provides visualizations that help in understanding the results of the SQL queries. The visualizations are designed to present the data in an accessible manner for non-technical stakeholders, allowing them to interpret the results easily.

## Technical Issues Encountered
While working with the datasets and the SQL queries, I faced the following technical challenges:

- MySQL Server & Workbench Issues: There were issues with loading large amounts of data into the MySQL server and MySQL Workbench. The datasets were too large to efficiently process, which limited my ability to run complex SQL queries or fully utilize the power of MySQL for large-scale data analysis.

- SQL Server Connection Issues with DAX (Power BI): Due to the technical difficulties with MySQL, I was unable to connect the SQL server to DAX (Power BI). This would have allowed for more dynamic and appealing visualizations, as well as the creation of an interactive dashboard.

## Alternative Approach with Anaconda Jupyter

Due to the above limitations, I had to use Anaconda Jupyter Notebooks to perform both SQL analysis and data visualizations. While this provided an alternative way to obtain the necessary results, it limited the ability to create more interactive, user-friendly dashboards that could be more appealing for stakeholders.

## Folder Structure
- cleaned_data.zip: Contains the cleaned datasets for users, transactions, and products.
- Data_Quality_check_&_transform.ipynb: Python notebook for data cleaning and transformation.
- SQL.ipynb: Python notebook with SQL queries for the closed-ended and open-ended questions.
- Visualizations.ipynb: Python notebook with visualizations of the SQL query results for easy interpretation.
## Conclusion
Despite the technical challenges, the datasets were thoroughly cleaned, SQL queries were successfully executed using SQLite, and insightful visualizations were created to help non-technical stakeholders interpret the data. The repository offers a complete analysis pipeline, from data processing to presenting the results in a user-friendly manner.
