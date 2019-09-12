# NYC-Job-Openings-Prediction-Model-in-R
Dataset – NYC Jobs

Link - https://data.cityofnewyork.us/City-Government/NYC-Jobs/kpav-sd4t

## Description:

I have analyzed this dataset from the NYC OpenData website. It contains current job postings available on the City of New York’s official jobs site. It has data from 2013 to 2018 when I was working on this project. It has 28 columns and 3675 rows.

## Analysis

Explored most of the variables which were relevant to the analysis. After dividing the job categories into IT and Non-IT fields, it is used the variables in relevance to the jobs available. Data analysis was done:  
1. To show the relationship between Work Location and IT and Non-IT Job Opening with graph and explanation. 
2. To Explore the average salary in each location both maximum and minimum on an annual and hourly basis. 
3. To Analyze jobs are based on timings - both part-time and full-time location wise. 
4. To Explore the relationship between salary frequency based on location. (what the salaries are paid in the 5 boroughs of NYC)

The outcomes of the project are as follows:
*	Manhattan and Brooklyn have maximum IT-related job openings whereas, for non-IT job openings, Manhattan and Queens have maximum job openings. The Bronx and Staten Island do not have IT and very few non-IT openings.
*	Manhattan has a maximum annual salary and a maximum hourly salary, and the Bronx has a minimum. 
*	Manhattan and Queens have maximum full-time job openings.


## Exploratory Analysis: 

* **NYC_Jobs_ORG.csv** - Messy data set which was downloded from OPEN nyc data
* **NYC_Jobs_clean.csv** - Clean data set after preprocessing the original data
* **Exploratory_analysis.Rmd** - R markdown file with exploratory analysis with detail explaination
* **Exploratory_analysis_report.pdf** - Exploratory Analysis report
* **Exploratory_analysis (knitted).pdf** - PDF report file, generated from rmd file

## Predictive Analysis (KNN Classification):

* **NYC_Jobs_2.csv** - Clean data 
* **Knn_classification.Rmd** - Built KNN classification model
* **KNN_prediction_report.pdf** - Predictive analysis report, explained result in detail
* **Knn_classification(knitted).pdf** - PDF report file, generated from rmd file

