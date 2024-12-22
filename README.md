# DataAnalyticsLN

### This is our Repository for the LN in Data Analytics. 
The authors are Alma Halimi, Dalina Ismaili and Ferzana Gehringer. In this repository we will work with notebooks to fulfill each point of the project.

Our idea is to use the API of https://www.unhcr.org to get data of refugees.
The documentation of the api:https://api.unhcr.org/docs/refugee-statistics.html _gl=1*1ks5dnr*_gcl_au*MTE1MzI1NjQzNS4xNzM0NjQ5NTY3*_rup_ga*MzgxNDU2Mzk4LjE3MzQ2NDk1Njc.*_rup_ga_EVDQTJ4LMY*MTczNDc0MzQ5My43LjEuMTczNDc0MzUxOS4zNC4wLjA.*_ga*MzgxNDU2Mzk4LjE3MzQ2NDk1Njc.*_ga_X2YZPJ1XWR*MTczNDc0MzQ5My43LjEuMTczNDc0MzUxOS4zNC4wLjA.

<br>
<b>Notebooks:
Refugee_Data -> Using the webapi by unhcr to get demographic data about refugees from specific countries and the countries they chose to flee to. (year 1998 till 2024).
--> Result = unhcr_refugee_detailed_data.csv

GDP_Data -> Using the webapi by worldbank to later (notebook data_preperation) enrich our existing data. To see if the asylum countries GDP has influence about how many refugees flee there.
--> Result = gdp_data_1998_2024.csv

Data_Preperation -> Data preparation (e.g. remove missing values and duplicates, create new variables, enrich the data with open data)
--> Result = prepared_refugee_data.csv (csv file unhcr_refugee_detailed_data cleaned and new variables added)
--> Result = cobined.csv (cobined data from gdp_data_1998_2024.csv and prepared_refugee_data.csv)
--> Result = refugee_data_and_gdp.csv (ultimate data from prepared_refugee_data.csv and cobined.csv)

Chi-Squared Test -> Performing a chi-sqaured test on the combined.csv file.
--> Result = test result

K-Means-Clustering -> Performing a K-Means-Clustering.
--> Result = clustered the data from the combined.csv file
</b>
</br>

The project must be a Data Analytics project, i.e., must include content of the Data Analytics module.

The project must integrate several topics presented in the module, at a minimum these are the following: 
(1) Data collection using Web Scraping and/or a Web API.

(2) Data preparation (e.g. remove missing values and duplicates, create new variables, enrich the data with open data).

(3) Data storage in a database like SQLite, MySQL or PostgreSQL.

(4) Rich non-graphical and graphical exploratory data analysis (EDA).

(5) Use of either regression or classification as the modeling method.

(6) Model evaluation using suitable measures of fit (e.g. r-squared, rmse, accuracy, recall, precision, ...)

(7) Correct interpretation of model results and measures of fit.

(8) Making the material (data, Jupyter notebooks, ...) available on Moodle.

Additional points, if the following criteria are met (max 5 points):

(1) Creativity of implementation (creative is anything not specified in the lessons and exercises).

(2) Use of a MySQL or PostgreSQL database (not SQLite!!!) for data storage and SQL-queries from within Python.

(3) Integration and visualization of geographical data.

(4) Use of a Chi-squared test or analysis of variance (ANOVA) or correlation analysis (each test must include a p-value).

(5) Use of k-means clustering in addition to the regression or classification model.