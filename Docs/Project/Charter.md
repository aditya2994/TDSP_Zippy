# Project Charter

## Business background

* The client is the Humana Marketing team.
* Business Problem - We are trying to predict the likelihood of someone responding to a maketing campaign to purchase MAPD (Medicare Advantage Plan that offers prescription drug coverage) or Med Supplement Insurance Plan during the Special Election Period from Dec 8 - Sep 30.

## Scope
* What data science solutions are we trying to build?
We are trying to build a Prospect ML mode to predict the likelihood of someone purchasing a MAPD or Med Supplement Insurance Plan 
* What will we do?
We will make use of four data sources and test multiple algorithms to build an effective prospect model.
* How is it going to be consumed by the customer? 
The marketing team will consume a web service API to populate the marketing database with consumer likelihood to respond to direct mail marketing campaigns. 

## Personnel
* Who are on this project:
	* Humana DS Team:
		* Project lead
		* PM
		* Data scientist(s)
		* Account manager
	* Humana Marketing Team:
		* Data administrator
		* Business contact
	
## Metrics
* What are the qualitative objectives? Improve effectiveness of direct mail marketing campaigns for Medicare Supplement and Medicare Part D plans through more effective ad targeting. 
* What is a quantifiable metric? Increase insurance plan sales in one year.
* Quantify what improvement in the values of the metrics are useful for the customer scenario? Increase insurance plan sales in one year by 20%
* What is the baseline (current) value of the metric? The current sales numbers are Y.
* How will we measure the metric? We will A/B test on two different subsets of data trained using different alogirithms We could also compare sales value (metric) after a specified time.

## Plan
* Phase 1 - Understand the business problem, get access to data, understand the data and preprocess the data
* Phase 2 - Build a model and deploy it

## Architecture
* Data
  * What data do we expect? CSV files in the Humana blob. We have four data sources combined to form one dataset.
  * after some pre-aggregation on-prem,
  * Sampled data enough for modeling 

* What tools and data storage/analytics resources will be used in the solution?
  * Azure Databricks
  * AzureML for modeling and web service operationalization
* How will the score or operationalized web service(s) (RRS and/or BES) be consumed in the business workflow of the customer? If applicable, write down pseudo code for the APIs of the web service calls.
  * How will the customer use the model results to make decisions? The marketing team will consume a web service API to populate the marketing database with consumer likelihood to respond to direct mail marketing campaigns. 
  * Data movement pipeline in production
  * Make a 1 slide diagram showing the end to end data flow and decision architecture
    
## Communication
* How will we keep in touch? Weekly meetings?
We will have a daily standup to discuss the goals for the day and what we accomplished the previous day. Also, there will be a biweekly stakeholder meeting.
* Who are the contact persons on both sides?
The Project Lead on the DS Team and the business contact on the marketing team.
