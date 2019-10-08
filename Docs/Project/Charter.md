# Project Charter

## Business background

* The client is the Humana Marketing team.
* Business Problem - We are trying to predict the likelihood of someone purchasing a MAPD (Medicare Advantage Plan that offers prescription drug coverage) or Med Supplement Insurance Plan during the Special Election Period from Dec 8 - Sep 30.

## Scope
* What data science solutions are we trying to build?
We are trying to build a Prospect ML mode to predict the likelihood of someone purchasing a MAPD or Med Supplement Insurance Plan 
* What will we do?
We will make use of four data sources and test multiple algorithms to build an effective prospect model.
* How is it going to be consumed by the customer? 
It will be uploaded to the marketing database and assessed to increase the effectiveness of their marketing campaigns.

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
* What are the qualitative objectives? Estimate the likeihood of someone purchasing an insurance plan.
* What is a quantifiable metric? Increase insurance plan sales in one year.
* Quantify what improvement in the values of the metrics are useful for the customer scenario? Increase insurance plan sales in one year by 20%
* What is the baseline (current) value of the metric? The current sales numbers are Y.
* How will we measure the metric? We will A/B test on a subset data that has not been trained with the trained data. We could also compare sales value (metric) after a specified time.

## Plan
* Phases (milestones), timeline, short description of what we'll do in each phase.

## Architecture
* Data
  * What data do we expect? Raw data in the customer data sources (e.g. on-prem files, SQL, on-prem Hadoop etc.)
* Data movement from on-prem to Azure using ADF or other data movement tools (Azcopy, EventHub etc.) to move either
  * all the data, 
  * after some pre-aggregation on-prem,
  * Sampled data enough for modeling 

* What tools and data storage/analytics resources will be used in the solution e.g.,
  * Databricks
  * AzureML for modeling and web service operationalization
* How will the score or operationalized web service(s) (RRS and/or BES) be consumed in the business workflow of the customer? If applicable, write down pseudo code for the APIs of the web service calls.
  * How will the customer use the model results to make decisions
  * Data movement pipeline in production
  * Make a 1 slide diagram showing the end to end data flow and decision architecture
    * If there is a substantial change in the customer's business workflow, make a before/after diagram showing the data flow.

## Communication
* How will we keep in touch? Weekly meetings?
* Who are the contact persons on both sides?
