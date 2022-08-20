# MAVEN AIRLINE PASSENGERS SATISFACTION ANALYSIS
![cheerful-woman-sitting-in-passenger-chair-in-airpl](https://user-images.githubusercontent.com/108612390/185735518-4e17e9c8-3a7c-4901-8411-d11b38b8634f.jpg)

# Introduction
This Analysis seeks to measure the satisfaction rate of 129,880 Maven Airline Passengers including additional information about each passenger,their flight and type of travel as well as their ratings of different services like cleanliness, comfort, service and overall airline experience. 

# The Dataset
The dataset imported for analysis was sourced from Maven playground website. It contains 1 CSV file, a single table structure, 129,880 records and 24 columns

# My approach for analysis
Understanding the purpose for Analysis:
The task of this analysis is to evaluate passengers satisfaction ratings,identify the factors which are not satisfactory and profer recommendations which the airline may execute to ensure customer satisfaction which would improve sales and patronage.
Having understood the task of this analysis, i proceeded to implore the following analytical tools to prepare the data for analysis
- Microsoft Excel: 
I utilized Excel to view and understand the parameters of my dataset i.e understand each of the 24 columns and check for their varying data types.
- PostgreSQL:
-  Postgresql is a great tool for eliminating duplicates, null values and outliers from a dataset which is a very significant aspect of analysis to improve data quality and accuracy. I successfully imported the dataset into postgresql, identified the primary key and searched for duplicates and irrelevant data.
![Screenshot (35)](https://user-images.githubusercontent.com/108612390/185739055-d95d4048-0cc2-42dd-814f-f25cfaafa3be.png)
The '0 rows affected' result shows there are no duplicates
Power BI: A bulk of my analysis and visualization was done on Power BI. I performed calculations using DAX formulas and utilized a few charts for visualization.
# Analysis
![Screenshot (37)](https://user-images.githubusercontent.com/108612390/185740434-9896976b-e368-4b07-ba9f-68ecca1a6324.png)
Click on the link below to interact with this analysis
- https://app.powerbi.com/view?r=eyJrIjoiZmU0YTRlMTktYTFjYS00YTQ5LWJiNzgtNGZkYjYzZjMzOTVkIiwidCI6IjI3MTZhMTNmLTBhOTMtNGZlMy1hYTMxLTQ4ZDgxNTA1ZTdlNiJ9&pageName=ReportSection

![Screenshot (41)](https://user-images.githubusercontent.com/108612390/185765749-a25d46ca-cc73-4f8c-88fa-c661f97ba17e.png)

- The Maven Airline dataset has a total of 129,880 records representing 129,880 passengers of which 51% are female and 49% are of the male gender. 

- Analyis shows that majority(76%) of the airline passengers are Adults,followed by Youth(11%), Children(8%) and the least number of persons are the Senior citizens with just (5%) of the total passengers.

- Returning passengers are 82% more than first-time passengers who are only 18%.

- Majority of the Passengers seem to prefer the Business and Economy class as they occupy 93% of the total passengers in contrast with Economy plus of just 7%.

![Screenshot (42)](https://user-images.githubusercontent.com/108612390/185765991-1641989c-ba33-41a0-b79e-8066f506288d.png)

- My analysis above shows that majority of the passengers board the short distance flight of less than 1000 miles. Apparently, the shorter the flight distance the more passengers on board and vice versa.

![Screenshot (43)](https://user-images.githubusercontent.com/108612390/185766126-affdbcfe-1fc9-4640-95de-89b748f5593f.png)

- On average, the returning passengers are more in numbers than the first-time passengers which shows that the airline is doing well with customer retention.

![Screenshot (38)](https://user-images.githubusercontent.com/108612390/185766193-93695e1c-11b3-44fe-80aa-8144cf6859f2.png)

- Satified passengers based on their ratings of the airline servies are 43% which is 14% lower than the Neutral/Dissatisfied passengers of 57%.

- On an evaluation of the survey done by the passengers based on the airline services, it appears that a majority of the passengers are very satisfied with the In-flight services, the Baggage handling, seat comfort,amongst others and Very dissatisfied majorly with the In-flight Wifi service, Online Bookings,Gate location, in that order.

# Recommendations;
- In-flight Wifi service is the worst rated with over 6% of the total passengers grossly dissatisfied with the service. This should be inspected, upgraded and improved to ensure a general satisfactory user experience by every age group.
- The processes of online booking should be properly checked, made easily accessible and readable for every age grade. This would make online bookings stress- free and definitely encourage more persons to use the online platforms for bookings and reduce customer churn.
- The Gate location has also been frowned on by majority of the passengers. A geo location guide should be introduced in the airline application as well as staffs at the airline ground to enable easy navigation of the airline premises.
- The percentage of first-time passengers is quite low. This should be addressed by making advert placements on media platforms to attract more customers and increase sales.
