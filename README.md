Problem Statement: Improve Healthcare:Using datasets provided at various sources [1] and [2], generate useful information regarding most deaths by diseases, by state.
Your foremost basic task is to create data, the datasets provided are very generalised and heterogenous so you have to do data cleaning and integration.
Create a system which dynamically shows predicted trends and provides a complete overview.
Flagged regions should be provided with better healthcare equipment and more doctors.
Predict nationwide disease outbreak and come up with a solution to counter if such an incident is to happen.We started with the sources to collect data regarding the statement but the data available was hetrogeneous and
scattered, we mined the data from https://www.indiastat.com, http://www.healthdata.org/india and https://data.gov.in
and cleaned it. We found out the correlation between the features with XGBoost and predicted the values of future time.
The data plots show the Highest effecting disease of a state the number of doctors available and the deaths that have happened.
The CSV file of the data collected is availabe in the repo.
indiastat.comindiastat.com
Socio Economic Statistical Data & Facts About India - e-Resource Library for Research | Indiastat
India's largest e-resource of Socio-economic statistical information & Data. A Comprehensive Insight On Demographics, Industries, Market, Agriculture, Economy and much more.
data.gov.indata.gov.in
data.gov.in
Open Government Data Platform (OGD) India is a single-point of access to Datasets/Apps in open format published by Ministries/Departments. Details of Events, Visualizations, Blogs, infographs.
Message Input
