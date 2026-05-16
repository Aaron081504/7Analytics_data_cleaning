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

1. Remove Unnecessary Columns
During preprocessing in Power Query, unnecessary columns such as:
id
Unnamed: 0
were removed because they did not contribute meaningful information to the analysis.

Reason:
 Removing non-essential columns optimized the dataset, reduced memory load, and simplified data modeling for an efficient dashboard experience.
2. Handle Missing Values
Missing values were detected in the Arrival Delay in Minutes column. These were replaced with 0 to ensure data consistency.

Reason:
 Replacing missing values prevents calculation and aggregation errors, ensuring that KPIs and visualizations are computed accurately.
3. Remove Duplicate Records
Duplicate entries were removed from the dataset using Power Query’s Remove Duplicates function.

Reason:
 Duplicate records can distort statistics and metrics. Eliminating them ensures that insights and satisfaction analyses are based on unique and accurate passenger data.
4. Verify and Adjust Data Types
All columns were checked and adjusted to appropriate data types:
Column Name
Correct Data Type
Age
Whole Number
Flight Distance
Whole Number
Customer Type
Text
Gender
Text
Departure Delay in Minutes
Whole Number
Arrival Delay in Minutes
Whole Number
Satisfaction
Text



Reason:
 Ensuring correct data types is crucial for proper aggregations, filtering, and visual computation logic within Power BI.
5. Create Relationships and Model Data
Relationships between relevant tables (if applicable) were built to connect customer details, flight information, and satisfaction metrics.

Reason:
 Data modeling allows Power BI to generate accurate cross-filtering and aggregated insights across different report visuals.
6. Develop Interactive Dashboard
An interactive Airline Passenger Satisfaction Analytics Dashboard was designed featuring:
Slicers: Gender, Satisfaction, and Customer Type filters
KPI Cards: Total Passengers, Satisfaction Rate
Bar Charts: Satisfaction by Class, Satisfaction by Delay
Pie Charts: Customer Type and Satisfaction Distribution
Combined Charts: Measure vs. Satisfaction Rate

Reason:
 Interactive visualizations allow users to easily explore airline performance, passenger satisfaction, and operational efficiency across multiple categories.
7. Insights and Impact
The completed dashboard provides actionable insights such as:
Satisfaction trends by travel class and customer type
Correlation between delays and satisfaction levels
Distribution of passenger demographics

Outcome:
 The analysis supports decision-making for improving airline service quality and customer experience.


