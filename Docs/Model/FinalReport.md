# Final Model Report
This is the final report describing the final model to be delivered - typically comprised of one or more of the models built during the life of the project.

## Analytic Approach
* What is target definition?
The likelihood of purchasing an insurance plan
* What are inputs? 
The inputs are from 4 data sources :
  * AMLK: Third party demographic data from vendor Amerilink
  * Campaign Data: Response and Conversion rates for direct mail marketing campaigns
  * Credit data: consumer credit data aggregated to the zip4 level
  * MACVAT: Medicare Part D and Medicare Supplement plan competitiveness based on actuarial calculations from vendor Milliman
* What kind of model was built? Binary classification model using XGBoost 
## Solution Description
* Simple solution architecture (Data sources, solution components, data flow)
  * Data Ingestion - Azure IoT Hub, Azure EventHub, Azure Data Factory, Azure Functions, Azure Stream Ananlytics
  * Data Storage - Data Lake Store, Azure Databricks, Azure Cosmos DB, Azure Data Warehouse
  * Data Science - Azure ML Service, Databricks, Azure SQL Database with ML Services, Azure Kubernetes Services 
  * Data Visualization and Serving - Azure Web Apps, Power BI, Azure analysis services
  * Security, Monitoring and Orchestration - Azure Active Directory, Azure DevOps, Application Insights, Azure Key Vault 
* What is output? Score denoting how likely someone is to respond to an ad campaign.

## Data
There are 4 data sources:
* AMLK : Amerilink - Third party demographic data
* Campaign data : Data from  marketing campaign
* Credit data : aggregated to zip4 level
* MACVAT : Actuarial calculation for every medicare advantage plan

There is one dataset that contains all the data from these sources and is stored in Humana >> at-dhasandbox-central-rg >> humana – Blobs >> synthetic.
There are 200000 rows and 287 columns in the dataset.

## Features
The 193 features used for modeling are:


## Algorithm
* Description or images of data flow graph
  * if AzureML, link to:
    * Training experiment
    * Scoring workflow
* What learner(s) were used?
* Learner hyper-parameters

## Results
* ROC/Lift charts, AUC, R^2, MAPE as appropriate
* Performance graphs for parameters sweeps if applicable

| | metrics  | train_score | test_score|
| ------------- | ------------- | ------------- |------------- |
| 0  | Accuracy|0.622375|0.596877|
| 1  | Precision|0.613559|0.602282|
| 2  | Recall|0.640463|0.605737|
| 3  | ROC|0.622555|0.596741|
| 4  | F1|0.626722|0.604004|

