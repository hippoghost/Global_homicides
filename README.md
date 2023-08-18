# Global_homicides SQL analysis

## Project overview

In this project, we will conduct a comprehensive data analysis of a homicide dataset from UNDATA using SQL. We chose this dataset for a number of reasons:

* The dataset is rich in insights
* The analysis has the potential to improve public safety
* The dataset is of public interest

We will use SQL to manipulate, query, and aggregate data, thus identifying trends and patterns, while DB Browser will facilitate data exploration.


## Data
The original file was an xls file that was converted and cleaned with the use of Python in two different csv files. The final csv that we used for our analysis was loaded in DB Browser for SQLITE.

### Dataset "intentional homicides count":

It is composed of 270 rows and 24 columns.

    Region - large geographic area that can contain multiple countries.
    Subregion - smaller geographic area within a region that can contain multiple countries or parts of a country.
    country - self-governing geographic area with distinct borders and a unique government.
    source - 
    year2000-year2020- absolute homicides number per year
    
 The final dataset consists of two CSV files that were joined together:

* number.csv - provides information about the total number of homicides per country, region, and subregion.
* rates.csv - contains information about the rates of homicides per country, region, and subregion.

 This allowed for greater clarity, readability, and understanding. All of the datasets used in this project can be found in our GitHub repository.
    
## Goals

* Show how to manipulate, query and aggregate data using SQL to identify trends and patterns.
* Demonstrate how to facilitate data exploration using DB Browser.
* Explain how to import and merge CSV files into a single dataset for complex analysis.
* Provide insights on homicide rates in various countries and regions by using SQL queries to filter and sort data.

## Business Applications

The project's insights have several potential business applications:

* Policymakers and law enforcement agencies can use the insights to allocate resources effectively and implement targeted crime prevention strategies.
* Researchers and analysts can further investigate the factors influencing changes in homicide rates over time.
* Organizations focused on public safety can leverage the findings to make data-driven decisions that contribute to safer communities.

Check my article on [MEDIUM](https://medium.com/@dimmakriss/unlocking-the-power-of-sql-part-2-analyzing-homicides-worldwide-using-sql-and-db-browser-a59199cbda9f)



## How to use the project

### Dataset Download:

* Start by downloading the homicide dataset [here](https://github.com/hippoghost/Global_homicides/blob/master/Americas_homicides.xlsx), [here](https://github.com/hippoghost/Global_homicides/blob/master/Intentional%20Homicide%20Victims%20by%20counts%20and%20rates%20p.xls) and [here](https://github.com/hippoghost/Global_homicides/blob/master/europe_homicides.xlsx) .
* Save the dataset on your local machine.

### Data Cleaning and Transformation:

* Open the Python script provided in the repository.
* Modify the script to load the dataset you downloaded.
* Run the script to perform basic data cleaning and transformation tasks.

### Database Creation and Import:

* Open DB Browser for SQLite.
* Create a new database and give it an appropriate name.
* Use the "Import" option to add the cleaned data as CSV files to the database. Ensure you follow the steps mentioned in the article to import the data correctly.

### Exploring Insights:

* Once you have the database set up, you can start exploring the data using SQL queries.
* Open the "Execute SQL" tab in DB Browser.
* Copy the SQL queries provided in the article or write your own to analyze the data. You can explore trends, compare homicide rates, and identify patterns.
  
### Interpreting Results:

* As you execute the SQL queries, the results will be displayed in tabular format.
Interpret the results to understand trends, compare regions, and identify countries with high or low homicide rates.

## Drawing Conclusions:

* Based on the insights gained, draw conclusions about the trends and patterns in homicide rates across different countries and regions.




## 🚀 About Me
Data analyst & Storyteller ┃ Pattern discoverer 
