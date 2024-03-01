# Customer-Clustering-Analysis
Developed a model for one of the retail store in Boulder to get sense of customers and classify them into different cohorts/groups so that suitable marketing strategies can be used for individual cohort.

![image](https://github.com/keshavsood80/Customer-Clustering-Analysis/assets/139059600/ac49072a-6f00-4c24-8d9a-dd1f689d0fc9)
![image](https://github.com/keshavsood80/Customer-Clustering-Analysis/assets/139059600/91d0b029-58d9-405c-9a8f-72ae01574152)


## Problem Statement

Walmart has asked us to develop a model for one of the retail store in Boulder. If they like your work, they will ask you to replicate the model for other Walmart retail stores as well 
You would like to develop a model to get sense of customers and classify them into different cohorts/groups 
You are given the following attributes for 2000 customers (based on the Loyalty card they use at checkout)


- Customer ID
- Sex/Gender
- Martial Status
- Education
- Income
- Occupation (Unskilled/Skilled/Highly skilled)
- Settlement Size (The size of the city that the customer lives in)


The model should be able to classify customers into different cohorts so that suitable marketing strategies can be used for individual cohort

### About Boulder:
- Boulder is a small town located in Colorado. Many high school and university students come to Boulder for attaining education
- After attaining education, students get placed in top-notch software companies in Boulder. 
- However, due to limited jobs in Boulder, some students look for job opportunity in their home-town cities or nearby big cities such as Louisville, Westminster, etc. These big cities are a few miles away from Boulder


## Dataset
Data Source : https://github.com/keshavsood80/Customer-Clustering-Analysis/blob/main/segmentation%20data.csv

## Understand the Variables 
| Variable	| Data type |	Range |	Description |
| --- | --- | --- | --- |
| ID	| numerical |	Integer |	Shows a unique identificator of a customer |
| Sex	| categorical |	{0,1}	| 0 - male ,	1	- female |
| Marital status |	categorical |	{0,1}	| 0 - single	, 1 -	non-single (divorced / separated / married / widowed) |								
| Age |	numerical	| Integer | The age of the customer in years |														
| Education |	categorical |	{0,1,2,3}	| Level of education of the customer -- 0	- other / unknown	, 1 -	high school, 2	- university , 3	- graduate school	|
| Income |	numerical | Real |	Self-reported annual income in US dollars of the customer |
| Occupation |	categorical |	{0,1,2} |	Category of occupation of the customer -- 0	- unemployed / unskilled , 1	- skilled employee / official	, 2 -	management / self-employed / highly qualified employee / officer	|
|Settlement size	| categorical |	{0,1,2}	| The size of the city that the customer lives in -- 0 - small city , 1 -	mid-sized city , 2 - big city |							

## Agenda
- Step 1: Import Libraries
- Step 2: Import Dataset 
- Step 3: Exploratory Data Analysis
- Step 4: Univariate Data Analysis
- Step 5: Bi-variate Analysis
- Step 6: Data Preparation
- Step 7: Modelling
- Step 8: Evaluate Performance

## Models used
- Hierarchical Clustering
- K-Means Clustering

# Solution
- **jupyter Notebook : [Customer_Clustering_Analysis.ipynb](https://github.com/keshavsood80/Customer-Clustering-Analysis/blob/main/Customer%20Clustering%20Analysis.ipynb)**
- **Please Go through [Customer_Clustering_HLDX.pptx](https://github.com/keshavsood80/Customer-Clustering-Analysis/blob/main/Customer%20Clustering%20HLDX.pptx) for more info.**


## Analysis of Clusters
![image](https://github.com/keshavsood80/Customer-Clustering-Analysis/assets/139059600/b1679738-812b-46bf-b11c-1a6b30013666)

| Cluster Name | Analysis |
| --- | --- |
| (0) Fewer opportunity | High school passed people employed mostly in low skilled jobs (living in small cities) |
|	(1) Career Focused | Single men focusing on only careers earning 2nd highest salary |
| (2) Well Settled | Married elder people with University+ education and High Income |
|	(3) Average |	High school passed people employed in skilled job (living in small and medium cities)	|





