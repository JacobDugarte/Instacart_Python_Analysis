![Logo of Instacart]r'/Users/jacob/Downloads/Instacart_Logo.png'

# Instacart_Python_Analysis
A Data Analysis Project using Python to analyze data from an online Grocery Basket, Instacart.
Instcart is an online grocery store that operates through an app. They have good sales historically but want to uncover more information about their sales patterns.

## Objective
Instacart, an online grocery store. The task is to perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.

## Data
We were provided with datasets that contained all the customer information:

- Orders
- Orders_Products_Prior
- Products
- Customers
- Departments

## Tools
- Language: Python
- Libraries: Pandas, Numpy, Seaborn, Matplotlib, and Scipy
- Software: Jupyter Notebooks and Excel

## Folders
The basket analysis was separated into the following folders:

- Project Management: Contains the Project Brief
- Data: Separated into Original and Prepared Data. These contain the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. NOTE: This folder has not been included
- Scripts: Contains all the Python coding involved for the entire analysis process
- Analysis: Contains the Visualizations used for developing insights and presenting on the final report
- Sent to client: Contains the Final Report in Excel

## Skills Demostrated
- Data Cleaning: We performed data cleaning tasks, which involved removing duplicates, addressing missing values, and rectifying mixed or erroneous data types.

- Data Merging: We carefully selected and prepared the data for merging, ensured the successful completion of the merge, and then exported the final merged dataset as a pkl (pickle) file.

- Exploratory Data Analysis: In this phase, we conducted a comprehensive exploration of the data. We calculated basic descriptive statistics such as maximum, minimum, quartiles, mean, and standard deviation for each variable. Additionally, we utilized various data visualization techniques, including histograms, scatterplots, as well as bar and line charts, to gain insights into the data distributions.

- Creation of New Variables: We organized the data by user, order, and department to facilitate in-depth analysis at each level. We aggregated the data to generate flags related to user ordering behaviors, such as identifying 'new customers' or 'loyal customers,' and demographic information like whether customers have 'babies' or are 'pet owners.' We verified the accuracy of the new variables through crosstabs and value counts.

- Data Visualization: To effectively communicate our findings, we employed Matplotlib and Seaborn libraries to craft a variety of visual representations, including histograms, line charts, and both vertical and horizontal bar charts. We also created stacked and 100% stacked bar charts as needed.

- Reporting the Results: Finally, we compiled our findings into an Excel file. This document not only provided answers to questions posed by the sales and marketing teams but also documented the data population flow, consistency checks, data wrangling processes, and the derivation of new columns.
