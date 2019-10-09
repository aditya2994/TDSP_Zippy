# Exit Report of Project <X> for Customer <Y>

Instructions: Template for exit criteria for data science projects. This is concise document that includes an overview of the entire project, including details of each stage and learning. If a section isn't applicable (e.g. project didn't include a ML model), simply mark that section as "Not applicable". Suggested length between 5-20 pages. Code should mostly be within code repository (not in this document).

Customer: Humana Marketing Team

Team Members: Humana Data Science Team

##	Overview

We are trying to predict the likelihood of someone responding to a marketing campaign to purchase a MAPD (Medicare Advantage Plan that offers prescription drug coverage) or Med Supplement Insurance Plan during the Special Election Period from Dec 8 - Sep 30 by bulding a prospect machine learning model. The team will then upload this to the marketing database and use the solution to increase effectiveness of their marketing campaigns.

##	Business Domain
Marketing

##	Business Problem

Estimate the likelihood of someone purchasing a MAPD (Medicare Advantage Plan that offers prescription drug coverage) or Med Supplement Insurance Plan during the Special Election Period from Dec 8 - Sep 30.

##	Data Processing
4 data sources -
AMLK (2017, 2018) 
Campaign Data (Who were targeted, who responded etc.)
Credit data
MACVAT
There is a lot of pre processing to remove dirty data.

##	Modeling, Validation
Tried XGBoost, Logistic Regression. XGBoost outperfromed other algorithms.

##	Benefits
	
###	Company Benefit (internal only. Double check if you want to share this with your customer)
<What did our company gain from this engagement? ROI, revenue,  etc\>

###	Customer Benefit
What is the benefit (ROI, savings, productivity gains etc)  for the customer? If just POC, what is estimated ROI? If exact metrics are not available, why does it have impact for the customer?\>

##	Learnings

### 	Project Execution
<Learnings around the customer engagement process\>

### Data science / Engineering
<Learnings related to data science/engineering, tips/tricks, etc\>


### Domain
<Learnings around the business domain, \>


### Product
<Learnings around the products and services utilized in the solution \>

###	What's unique about this project, specific challenges
<Specific issues or setup, unique things, specific challenges that had to be addressed during the engagement and how that was accomplished\>

##	Links
<Links to published case studies, etc.; Link to git repository where all code sits\>


##	Next Steps
 
<Next steps. These should include milestones for follow-ups and who 'owns' this action. E.g. Post- Proof of Concept check-in on status on 12/1/2016 by X, monthly check-in meeting by Y, etc.\>

## Appendix
<Other material that seems relevant – try to keep non-appendix to <20 pages but more details can be included in appendix if needed\>
