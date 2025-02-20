# G_Suite_Metrics

Reference for data set:

https://developers.google.com/admin-sdk/reports/v1/reference/usage-ref-appendix-a/customers

Description of the project.

G Suite is a set of cloud computing, productivity and collaboration tools, software and products developed by Google. G Suite comprises Gmail, Drive, Docs, Calendar, Hangouts Chat, Hangouts Meet, Mobile, Voice, Slides, Sites, Sheets, Keep and Tasks, Groups, Google+, Forms, Contacts, Cloud Search, Chrome Browser. We are mainly focusing on the metrics Drive, Meet, Gmail, Accounts and Calendar.
Currently, Source Data for Google (G Suite) report metrics is pulled automatically into Splunk from Google on daily basis.

Below are the details of Data Set which we are using for this project

•	Size: 611,914 rows and 649 metric names.

•	Date Range: March 23rd, 2015 to August 17th, 2019

•	Fields: timestamp, metric_name, metric_value

Project Goals: 

1.	Performing Analysis on the data set.

2.	Finding Anomalies by comparing the values in the data set using timestamp, metric_name and metric_value.

3.	Prediction of future metric value based on the current data set values.

4.	Visualization / simple dashboard development from the findings using Google Data Studio 

We are team of 5 enthusiastic Computer science students we are working towards improving our skills in the field of data science.   

Dashboard Link:

https://datastudio.google.com/reporting/fe89e59f-5ab0-4f5e-bd70-9154c80fd02a

•	Software Requirements

Required modules:

•	pip install pandas:
Useful for various data scrubbing functionality.

•	pip install numpy:
Used to perform the basic statistical analysis

•	pip install scipy : 
The stats in scipy are used for the distibution modelling

•	pip install matplotlib : 
Used for the plots

•	Fb Prophet : 
Used for Predictive time series analysis.

Team Name:

OG_Suites

Team Members: 

•	Lavanya Goluguri(Google Drive) - https://github.com/UNCG-CSE/G_Suite_Metrics/tree/Gsuite_lavanyagoluguri

•	Anusha Vanama(Google Meet) - https://github.com/UNCG-CSE/G_Suite_Metrics/tree/Gsuite_AnushaVanama

•	Jackie Cuong(Google calendar) - https://github.com/UNCG-CSE/G_Suite_Metrics/tree/Gsuite_JackieCuong

•	Hieu Vo(Google Accounts) - https://github.com/UNCG-CSE/G_Suite_Metrics/tree/Gsuite_Hieu

•	Henry Reichard(Gmail) - https://github.com/UNCG-CSE/G_Suite_Metrics/tree/Gsuite_Henry

•	Instructor: Dr. Somya Mohanty

•	Advisor: Nick Young
