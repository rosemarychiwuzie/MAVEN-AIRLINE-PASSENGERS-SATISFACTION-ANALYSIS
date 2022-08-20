# MAVEN AIRLINE PASSENGERS SATISFACTION ANALYSIS
![cheerful-woman-sitting-in-passenger-chair-in-airpl](https://user-images.githubusercontent.com/108612390/185735518-4e17e9c8-3a7c-4901-8411-d11b38b8634f.jpg)

# Introduction
This Analysis seeks to measure the satisfaction rate of 129,880 Maven Airline Passengers including additional information about each passenger,their flight and type of travel as well as their ratings of different services like cleanliness, comfort, service and overall airline experience. 

# The Dataset
The dataset imported for analysis was sourced from Maven playground website. It contains 1 CSV file, a single table structure, 129,880 records and 24 columns

# My approach for analysis
Understanding the purpose for Analysis:
The task of this analysis is to evaluate passengers satisfaction ratings,identify the factors which are not satisfactory and profer recommendations which the airline may execute to ensure customer satisfaction which would improve sales and patronage.
On understanding the task of this analysis, i proceeded to implore the following analytical tools to prepare the data for analysis
- Microsoft Excel: 
I utilized Excel to view and understand the parameters of my dataset i.e understand each of the 24 columns and check for their varying data types.
- PostgreSQL:
 Postgresql is a great tool for cleaning a dataset of duplicates, null values and outliers which is a very significant aspect of analysis to improve data quality and accuracy. I successfully imported the dataset into postgresql, identified the primary key, searched for duplicates and irrelevant data.
![Screenshot (35)](https://user-images.githubusercontent.com/108612390/185739055-d95d4048-0cc2-42dd-814f-f25cfaafa3be.png)
The '0 rows affected' result shows there are no duplicates
Power BI: A bulk of my analysis and visualization was done on Power BI. I performed calculations using the DAX function and utilized a few charts for visualization.
# Analysis
![Screenshot (37)](https://user-images.githubusercontent.com/108612390/185740434-9896976b-e368-4b07-ba9f-68ecca1a6324.png)
Click on the link below to interact with this analysis
- https://app.powerbi.com/view?r=eyJrIjoiZmU0YTRlMTktYTFjYS00YTQ5LWJiNzgtNGZkYjYzZjMzOTVkIiwidCI6IjI3MTZhMTNmLTBhOTMtNGZlMy1hYTMxLTQ4ZDgxNTA1ZTdlNiJ9&pageName=ReportSection

- The Maven Airline has a total of 129,880 passengers of which 51% were female and 49% were of the male gender. 
- Satified passengers based on their ratings of the airline servies are 43% which is 14% lower than the Neutral/Dissatisfied passengers of 57%.
- Analyis shows that majority(76%) of the airline passengers are Adults,followed by Youth - 11%, Children - 8% and the least number of persons are the Senior citizens with just 5% of the total passengers.
- On an evaluation of the survey done by the passengers based on the airline services, it appears that a majority of the passengers are very satisfied with the In-flight services, the Baggage handling, seat comfort,etc and Very dissatisfied majorly with the In-flight Wifi service, Online Bookings,Gate location, in that order.

# Recommendations;
In-flight Wifi service is the worst rated 
