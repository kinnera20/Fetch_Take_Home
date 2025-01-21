# Fetch_Take_Home_Assessment
## Overview
This repository contains cleaned datasets, and Python notebooks, and SQL queries for data analysis and visualization related to a series of questions in a take-home assessment. The main components of the repository are as follows:

- Cleaned Datasets (ZIP file): The datasets for users, transactions, and products have been cleaned and processed. These datasets are packaged into a zip file for easy access.

- Python Notebook - Data_Quality_check_&_transform.ipynb: This notebook contains the Python code used to clean and transform the datasets. It covers tasks such as handling missing values, removing duplicates, standardizing data types, and ensuring that the datasets are properly formatted for analysis.

- Python Notebook - SQL.ipynb: This notebook contains the SQL queries used to answer both closed-ended and open-ended questions posed in the assessment. The queries were executed using SQLite, as an alternative to working with MySQL servers due to some technical limitations.

- Python Notebook - Visualizations.ipynb: This notebook provides visualizations that help in understanding the results of the SQL queries. The visualizations are designed to present the insights in an accessible manner for non-technical stakeholders, allowing them to interpret the results easily.

## Technical Considerations & Alternative approaches:
While working with the datasets and the SQL queries, I faced the following technical challenges:

- MySQL Server & Workbench Issues: I ran into issues uploading the datasets into MySQL Workbench, possibly due to their large size. After spending considerable time trying to troubleshoot the problem, I started looking into alternatives and came up with the idea of using Jypter. 

- SQL Server Connection Issues with DAX (Power BI): Initially, I planned on connecting SQL server to DAX within Power BI for interactive and easy-to-understand visualizations. However, this was not possible due to technical concerns sue to inconsistent updates in my servers . Exploring my next options, I settled upon using Python for accessible visualizations, forgoing the dynamic aspect. 

## Folder Contents:
- cleaned_data.zip: Contains the cleaned datasets for users, transactions, and products.
- Data_Quality_check_&_transform.ipynb: Python notebook for data cleaning and transformation.
- SQL.ipynb: Python notebook with SQL queries for the closed-ended and open-ended questions.
- Visualizations.ipynb: Python notebook with visualizations of the SQL query results for easy interpretation.
- Power point:
- word -that has drafted email
  
## Conclusion
Despite facing technical challenges, I was able to thoroughly clean the datasets, successfully execute SQL queries using SQLite, and create insightful visualizations to help non-technical stakeholders interpret the data. The repository offers a complete analysis pipeline, from data processing to presenting the results in a user-friendly manner.
