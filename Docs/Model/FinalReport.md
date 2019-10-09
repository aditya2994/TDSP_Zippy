# Final Model Report
This is the final report describing the final model to be delivered - typically comprised of one or more of the models built during the life of the project.

## Analytic Approach
* What is target definition?
The likelihood of purchasing an insurance plan
* What are inputs? All the features have been included in the data dictionary.
* What kind of model was built? Prospect Model using XGBoost

## Solution Description
* Simple solution architecture (Data sources, solution components, data flow)
* What is output?

## Data
There are 4 data sources:
* AMLK : Amerilink - Third party demographic data. It is unethical to use race to model the data.
* Campaign data : promotion
	3 variables
	Marketing campaign sent to prospects - direct mail
	Mailed to addresses and individuals (65-85)
	Logged when they dial that number - capture - response variable
	2 levels of response
	Prospect picked up phone
	Conversion
* Credit data : aggregated to zip4 - zip4 level
	Data is at the individual/consumer level
* MACVAT :
	Company called millimin
	Actuarial calculation for every medicare advantage plan
	Richness - actuarial value
	Determine if worse or better than a competitor
	Min vacvat - one of the better
	This is competitive
	Good predictor
	Dollar value in actuarial terms
	Rank dollar value against other plans in that county
	Minimum of humana's rank
 if in the top 3 for accounting
	If outside of top 10 - don’t get top sales
	1 to 20
	Best rank

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

