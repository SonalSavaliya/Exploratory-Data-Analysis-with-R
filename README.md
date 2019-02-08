# NYC-Job-Openings-Prediction-Model-in-R
Dataset – NYC Jobs

Link - https://data.cityofnewyork.us/City-Government/NYC-Jobs/kpav-sd4t

## Description:

This dataset from NYC OpenData website and analyzed it. It contains current job postings available in the City of New York’s official jobs site. It has data from 2013 to 2018. It has 28 columns and 3675 rows.

## Analysis

Explored most of the variables which were relevant to analysis. After dividing the job categories into IT and Non-IT fields, it is used the variables in relevance to the jobs available. I got to know about what are the salaries paid in 5 boroughs of NYC. What is maximum or minimum etc. 
Here are the findings - 
1. Got to know the relationship between Work Location and IT and Non IT Job Opening with graph and explaination. 
2. Explored the average salary in each locations both maximum and minimum on annual and hourly basis. 
3. Analysed jobs based on timings - both part-time and full time location wise. 
4. Explored the relashionship between salary frequency based on location.

## Exploratory Analysis: 

* **NYC_Jobs_ORG.csv** - Messy data set which was downloded from OPEN nyc data
* **NYC_Jobs_clean.csv** - Clean data set after preprocessing the original data
* **project1_exploratory_analysis.Rmd** - R markdown file with exploratory analysis with detail explaination
* **Project_report.docx** - Exploratory Analysis report
* **project1_exploratory_analysis.html** - HTML report file, generated from rmd file

## Predictive Analysis (KNN Classification):

* **NYC_Jobs_2.csv** - Clean data 
* **project_2.Rmd** - Built KNN classification model
* **Project_2.docx** - Predictive analysis report, explained result in detail
