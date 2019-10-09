# Data Report
This file will be generated for each data file received or processed.  [The Interactive Data Exploration, Analysis, and Reporting (IDEAR)](https://github.com/Azure/Azure-TDSP-Utilities) utility developed by TDSP team of Microsoft can help you explore and visualize the data in an interactive way, and generate the data report along with the process of exploration and visualization. 

[IDEAR](https://github.com/Azure/Azure-TDSP-Utilities) allows you to output the data summary, statistics, and charts that you want to use to tell the data story into the report. You only need to click a few buttons, and the report will be generated for you. 

## General summary of the data
There is one dataset with data from 4 sources which are - 
* AMLK: Third party demographic data from vendor Amerilink
* Campaign Data: Response and Conversion rates for direct mail marketing campaigns
* Credit data: consumer credit data aggregated to the zip4 level
* MACVAT: Medicare Part D and Medicare Supplement plan competitiveness based on actuarial calculations from vendor Milliman
  
 The dataset is already preprocessed. It has 200k rows and 287 columns.

## Data quality summary

### Read and Summarize the data
* Read data and infer column types
* Print the dimensions of the data
* Print the column names and types
* Extract Descriptive Stats for each column (numerical, categorical)


## Target variable

The target variable is resp_dvar. It is the likelihood to respond to a marketing campaign.

## Individual variables

* Explore the target variable
* Explore individual numeric variables and test for normality
* Explore individual categorical variables 

## Variable ranking

## Relationship between explanatory variables and target variable
### Explore Interactions Between Variables
* Rank variables based on linear relationships with reference variable
* Explore interactions between categorical variables
* Explore interactions between numerical variables
* Explore correlation matrix between numerical variables
* Explore interactions between numerical and categorical variables
* Explore interactions between two numerical variables and a categorical variable
* Project data to 2-D principal component space
* Project data to 3-D principal component space
