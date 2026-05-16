Final Project Documentation Report using Microsoft Power BI Desktop


Airline Passenger Satisfaction Analytics Dashboard


Course:
Bachelor of Science in Computer Science
Tool Used:
Microsoft Power BI Desktop
Dataset:
Airline Passenger Satisfaction Dataset

Prepared By:

Catacutan, Nathan
Magtoto, Aaron Patrick P.
Lopez, Leshune Kyle
Tapnio, Sherwein Clyde
Tuazon, Ranniel L.

Instructor:
Mrs. Marsha L. Superio

Summary
This project presents a comprehensive Airline Passenger Satisfaction Analytics Dashboard developed using Microsoft Power BI Desktop to analyze passenger satisfaction trends, customer behavior, flight delays, and inflight service quality using a real-world airline dataset containing more than 100,000 passenger records.
The analysis aimed to identify the major factors affecting airline passenger satisfaction and provide data-driven recommendations that may help improve airline customer experience and operational efficiency.
Using preprocessing techniques based on the CLEAN framework, the dataset was transformed into a structured analytical model suitable for business intelligence analysis. Multiple DAX measures and interactive dashboards were developed to evaluate relationships among travel class, customer type, delays, inflight services, and satisfaction levels.
The findings revealed that passengers experiencing fewer delays and better inflight services demonstrate higher satisfaction rates, while economy-class passengers tend to report lower satisfaction compared to business-class passengers. The dashboard enables airline administrators and analysts to monitor customer satisfaction trends and identify key areas requiring improvement.

Introduction
Airline passenger satisfaction has become an important factor in evaluating airline service quality and customer experience. Airlines continuously seek data-driven strategies to improve customer retention, reduce complaints, and enhance operational performance.
This project focuses on developing an interactive Airline Passenger Satisfaction Analytics Dashboard using Microsoft Power BI Desktop. The dashboard analyzes passenger data and visualizes trends related to customer satisfaction, flight delays, service quality, customer loyalty, and travel class.
The primary objectives of this project are:
1.	To preprocess and clean airline passenger data using the CLEAN framework. 
2.	To design a star-schema-inspired data model suitable for analytical reporting. 
3.	To create DAX measures for KPI monitoring and passenger satisfaction analysis. 
4.	To develop interactive dashboards for airline performance evaluation. 
5.	To generate actionable insights and recommendations based on passenger satisfaction trends. 
Dataset Description
The dataset used in this project is the Airline Passenger Satisfaction Dataset obtained from Kaggle and contains more than 100,000 passenger records with multiple airline service indicators.
Attribute	Description
Dataset Name	Airline Passenger Satisfaction Dataset
Total Records	100,000+
File Type	CSV
Data Type	Structured Tabular Dataset
Main Target Variable	satisfaction

Dataset Features
The dataset includes:
•	Passenger demographics 
•	Customer type 
•	Travel class 
•	Flight distance 
•	Inflight service ratings 
•	Delay information 
•	Passenger satisfaction status 

Key Variables
Column Name	Description
Gender	Passenger gender
Age	Passenger age
Customer Type	Loyal or disloyal customer
Type of Travel	Business or personal travel
Class	Economy, Economy Plus, Business
Flight Distance	Flight travel distance
Inflight wifi service	Wifi service rating
Seat comfort	Seat comfort rating
Food and drink	Food quality rating
Departure Delay in Minutes	Flight departure delay
Arrival Delay in Minutes	Flight arrival delay
satisfaction	Satisfied or dissatisfied passenger

Passenger Satisfaction Distribution
Satisfaction Status	Description
Satisfied	Passengers satisfied with airline services
Neutral or Dissatisfied	Passengers dissatisfied with airline services
The dataset indicates that customer satisfaction is strongly influenced by flight delays, travel class, and inflight service quality.

Data Collection
The dataset was imported into Microsoft Power BI Desktop through the Text/CSV connector.
Data Import Procedure
1.	Opened Power BI Desktop 
2.	Selected Home → Get Data → Text/CSV 
3.	Imported the Airline Passenger Satisfaction Dataset 
4.	Verified delimiter and encoding settings 
5.	Loaded dataset into Power Query Editor for preprocessing 
The dataset satisfies the project requirement of using a large real-world dataset with more than 100,000 records.

Data Preprocessing Using the CLEAN Framework
The dataset was preprocessed using the CLEAN framework to ensure data quality, consistency, and analytical readiness.

Completeness
Completeness ensures that the dataset contains minimal missing values.
Actions Performed
•	Checked column quality using Power Query Editor 
•	Verified missing values 
•	Identified null values in Arrival Delay in Minutes 
Result
Null values were successfully handled by replacing missing entries with 0.

Legitimacy
Legitimacy validates whether the dataset contains duplicate or invalid records.
Actions Performed
•	Removed duplicate rows using Remove Duplicates 
•	Removed unnecessary columns: 
o	Unnamed: 0 
o	id (optional) 
Result
Duplicate records and unnecessary columns were successfully removed.

Efficiency
Efficiency focuses on proper formatting and optimization.
Actions Performed
•	Assigned proper data types: 
o	Whole Number 
o	Text 
o	Decimal Number 
•	Verified numerical and categorical fields 
Result
The dataset became optimized for dashboard performance and analysis.

Accuracy
Accuracy ensures consistent analytical representation.
Actions Performed
•	Verified categorical consistency 
•	Checked valid passenger satisfaction categories 
•	Verified travel class consistency 
Result
The dataset became analytically reliable and consistent.

Normalization
Normalization was applied for future scalability and analytical consistency.

Data Modeling
A star-schema-inspired model was implemented inside Power BI to optimize dashboard responsiveness and analytical performance.
Main Table
The dataset contains passenger satisfaction observations and airline service ratings.

Benefits of the Data Model
•	Faster query performance 
•	Simplified filtering 
•	Improved DAX calculations 
•	Better dashboard responsiveness 
•	Improved scalability 

DAX Measures and KPI Development
Several DAX measures were developed to evaluate airline performance and passenger satisfaction trends.

Core KPI Measures
Measure	Purpose
Total Passengers	Counts total passengers
Satisfaction Rate	Calculates satisfied passenger percentage
Average Delay	Calculates average arrival delay
Satisfied Count	Counts satisfied passengers

Service Analysis Measures
Measure	Purpose
Average Seat Comfort	Evaluates comfort ratings
Average Wifi Service	Evaluates wifi quality
Average Food Rating	Evaluates food service

Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to identify trends and passenger behavior patterns.
Metric	Analysis
Satisfaction Rate	Passenger satisfaction percentage
Average Delay	Average delay experienced
Customer Type Distribution	Loyal vs disloyal customers
Travel Class Comparison	Satisfaction comparison by class

Cross-Analysis Findings
Flight Class and Satisfaction
•	Business-class passengers showed the highest satisfaction levels. 
•	Economy passengers demonstrated lower satisfaction rates. 

Delays and Satisfaction
•	Passengers experiencing higher delays were more likely to report dissatisfaction. 
•	Lower delays improved customer experience. 

Customer Loyalty
•	Loyal customers demonstrated higher satisfaction rates compared to disloyal customers. 

Inflight Services
•	Seat comfort, wifi service, and food quality strongly affected passenger satisfaction. 

Dashboard Design and Visualization
The dashboard was designed following the DASH Framework principles.
Framework Element	Implementation
Data-Driven	All visuals connected to KPIs and measures
Audience-Focused	Designed for airline administrators
Story-Driven	Structured from overview to detailed analysis
Hierarchy	KPIs prioritized at the top

Summary Dashboard
This page provides a high-level overview of airline passenger satisfaction.
Included Visuals
•	KPI Cards 
•	Bar Charts 
•	Pie Charts 
•	Line Charts 
•	Interactive Slicers 
Purpose

To provide airline administrators with a quick overview of customer satisfaction and operational performance.
Passenger Satisfaction Analysis
This page examines major factors affecting passenger satisfaction.
Included Visuals
•	Class vs Satisfaction 
•	Delay Trends 
•	Customer Type Distribution 
•	Satisfaction Distribution 
Purpose

To identify major contributors to customer satisfaction and dissatisfaction.
Dashboard Features
•	KPI Cards 
•	Interactive charts 
•	Slicers and filters 
•	Professional dashboard layout 
•	User-friendly interface 

Insights and Recommendations
1. Business-Class Passengers Have Higher Satisfaction
Business-class passengers demonstrated significantly higher satisfaction rates.
Recommendation
Improve economy-class services and seating comfort.

2. Flight Delays Reduce Passenger Satisfaction
Passengers experiencing longer delays showed lower satisfaction levels.
Recommendation
Improve scheduling efficiency and reduce operational delays.

3. Inflight Services Affect Customer Experience
Passengers rated seat comfort, wifi service, and food quality as important satisfaction factors.
Recommendation
Upgrade inflight services and customer support.

4. Loyal Customers Show Better Satisfaction
Loyal customers demonstrated better overall airline experience.
Recommendation
Improve airline loyalty programs and customer rewards.

Conclusion
This project successfully demonstrated the use of Microsoft Power BI Desktop for airline passenger satisfaction analytics and dashboard development.
Through data preprocessing, DAX calculations, interactive dashboards, and visualization techniques, meaningful insights were generated regarding airline customer satisfaction trends and operational performance.
The findings indicate that delays, travel class, customer loyalty, and inflight service quality strongly influence passenger satisfaction. The dashboard provides airline administrators with a powerful decision-support tool capable of monitoring customer experience and identifying service improvement opportunities.
