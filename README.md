# Problem Statement: 
Improve Healthcare-Using datasets provided at various sources [1] and [2], generate useful information regarding most deaths by diseases, by state.
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
# Plots
![newplot(1)](https://user-images.githubusercontent.com/26704802/55676949-3c689300-58fc-11e9-95b9-4c14cd1f9c54.png)

![newplot(2)](https://user-images.githubusercontent.com/26704802/55676966-949f9500-58fc-11e9-945a-1ee116b2dd30.png)

