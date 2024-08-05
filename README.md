# Instacart-Analysis
Python notebooks with data wrangling, cleaning, and visualizations created for an analysis of Instacart's business for a course on CareerFoundry.

# Objective
Instacart is an online grocery store that currently has very good sales numbers, but are looking to uncover more information about any sales patterns to further increase growth. My task, as a data analyst working on this project, is to perform an initial data and exploratory analysis of some of their data to dicover and derive any insights from the data and suggest strategies for better segmentation based on the provided criteria.

# Key Questions
The following questions were of particular focus for the analysis:
*  The sales team needs to know what the busiest days of the week are and what hours are the busiest times of day (which days and hours of the week have the most orders submitted) in order to optimize running advertisements during less busy days/times.
  
*  Are there specific times of the day when people spend the most money, as this can also impact which products are being advertised during those times.

*  Instacart has a lot of products with different price tags. Marketing and sales want to use simpler price range groupings to help direct their efforts.

*  Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.

*  The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviors differ. For example:
      *  What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?
      *  Are there differences in ordering habits based on a customer’s loyalty status?
      *  Are there differences in ordering habits based on a customer’s region?
      *  Is there a connection between age and family status in terms of ordering habits?
      *  What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
      *  What differences can you find in ordering habits of different customer profiles? Consider the price of orders, the frequency of orders, the products customers are ordering, and anything else you can think of.

# Data Sources
The datasets used in the analysis are:
      *  Customers
      *  Departments
      *  Orders
      *  Orders_products_prior
      *  Products

# Tools Used
I analyzed the data using the Anaconda distrobution of Python with the following libraries:
      *  Pandas - for data analysis
      *  NumPy - for mathematical equations
      *  SciPy - for data equations
      *  Seaborn - for data visulizations
      *  Matplotlib - for data visualizations

# Folders
The project files are broken down into the following folders:
      *  01 Project Management - contains the project brief documentation detailing the analysis
      *  02 Data - this folder is seperated into two subfolders, original data and prepared data. Original data contains the original dataframes before any analysis and manipulation while prepared data contains the dataframes after they have been cleaned and prepared for analysis. Due to the size of the dataframes, the data folder has not been uploaded to GitHub.
      *  03 Scripts - contains the Jupyter notebooks containing the coding for the analysis and visualizations.
      *  04 Analysis - contains a subfolder called Visualizations that contain all of the graphs and graphics used when developing the final presentation with my insights.
      * 05 Sent to Client - this folder contains the final presentation sent to the client in an Excel format.

# Resources
While Instagram is an actual company that has made their data available online, the customer data, the pricing information in the products dataset, and project brief have all been fabricated by CareerFoundry for the purposes of this analysis.
