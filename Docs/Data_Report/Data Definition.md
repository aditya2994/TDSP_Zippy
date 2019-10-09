# Data and Feature Definitions

This document provides a central hub for the raw data sources, the processed/transformed data, and feature sets. More details of each dataset is provided in the data summary report. 

For each data, an individual report describing the data schema, the meaning of each data field, and other information that is helpful for understanding the data is provided. If the dataset is the output of processing/transforming/feature engineering existing data set(s), the names of the input data sets, and the links to scripts that are used to conduct the operation are also provided. 

When applicable, the Interactive Data Exploration, Analysis, and Reporting (IDEAR) utility developed by Microsoft is applied to explore and visualize the data, and generate the data report. Instructions of how to use IDEAR can be found [here](). 

For each dataset, the links to the sample datasets in the _**Data**_ directory are also provided. 

_**For ease of modifying this report, placeholder links are included in this page, for example a link to dataset 1, but they are just placeholders pointing to a non-existent page. These should be modified to point to the actual location.**_


## Raw Data Sources


| Dataset Name | Original Location   | Destination Location  | Data Movement Tools / Scripts | Link to Report |
| ---:| ---: | ---: | ---: | -----: |
| ZipPy | * Resource Group: at-dhasandbox-central-rg *Storage Account Name: humana – Blobs * Blob Name: Synthetic | * Resource Group: at-dhasandbox-central-rg * Storage Account Name: humana – Blobs * Blob Name: Synthetic|[Synthetic ZipPY.dbc](https://github.com/aditya2994/TDSP_Zippy/blob/master/Code/Modeling/Synthetic%20ZipPy.dbc) | [Data Report]( https://github.com/aditya2994/TDSP_Zippy/blob/master/Docs/Data_Report/DataSummaryReport.md)  

* The dataset is comprised of data from four different sources - AMLK (2017, 2018), Campaign Data (Who were targeted, who responded etc.), Credit data, and MACVAT. The data is already preprocessed and is stored in -
  * Resource Group: at-dhasandbox-central-rg 
  * Storage Account Name: humana – Blobs 
  * Blob Name: Synthetic 


A brief decription of the data sources -
* AMLK: Third party demographic data from vendor Amerilink 
* Campaign data : Response and Conversion rates for direct mail marketing campaigns
* Credit data : consumer credit data aggregated to the zip4 level
* MACVAT: Medicare Part D and Medicare Supplement plan competitiveness based on actuarial calculations from vendor Milliman
	
## Processed Data
| Processed Dataset Name | Input Dataset(s)   | Data Processing Tools/Scripts | Link to Report |
| ---:| ---: | ---: | ---: | 
| ZipPy |ZipPy|[Synthetic ZipPY.dbc](https://github.com/aditya2994/TDSP_Zippy/blob/master/Code/Modeling/Synthetic%20ZipPy.dbc) | [Data Report]( https://github.com/aditya2994/TDSP_Zippy/blob/master/Docs/Data_Report/DataSummaryReport.md)  

* The dataset is comprised of data from four different sources - AMLK (2017, 2018), Campaign Data (Who were targeted, who responded etc.), Credit data, and MACVAT. The data is already preprocessed and is stored in -
  * Resource Group: at-dhasandbox-central-rg 
  * Storage Account Name: humana – Blobs 
  * Blob Name: Synthetic 


## Feature Sets

| Feature Set Name | Input Dataset(s)   | Feature Engineering Tools/Scripts | Link to Report |
| ---:| ---: | ---: | ---: | 
| ZipPy |ZipPy|[Synthetic ZipPY.dbc](https://github.com/aditya2994/TDSP_Zippy/blob/master/Code/Modeling/Synthetic%20ZipPy.dbc) | [Data Report]( https://github.com/aditya2994/TDSP_Zippy/blob/master/Docs/Data_Report/DataSummaryReport.md)  

* The dataset is comprised of data from four different sources - AMLK (2017, 2018), Campaign Data (Who were targeted, who responded etc.), Credit data, and MACVAT. The data is already preprocessed and is stored in -
  * Resource Group: at-dhasandbox-central-rg 
  * Storage Account Name: humana – Blobs 
  * Blob Name: Synthetic 

