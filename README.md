# Surfs_up!!

### Oahu Hawaii weather data analysis for location viability of potential of "surf and scoop shop" business.

### Project overview

#### Customer request: 
 - To analyze weather data (specifically temperature) on Oahu island in Hawaii.

#### Purpose: 
 - To identify and analyze temperature trends for the months of June and December.  The analysis of these two months as peaks will be used to determine if the weather data justifies and supports year round operation of the "Surf and Scoop" proposed surfing and ice cream shop business.

#### Method:
 - Using Python, Pandas, and SQLAlchemy to Extract and Analyze the data.

#### Resources
 - Data Source: hawaii.sqlite;
 - Source Code: SurfsUp_Challenge;
 - Software: Python 3.7.9 64-bit (conda); jupyter-notebook : 6.1.4
 - SQLite Database

### Results
#### June (Deliverable 1)
 - Average Temperature = 74.9 deg F
 - Maximum Temperature = 85.0 deg F
 - Minimum Temperature = 64.0 deg F


![image](https://user-images.githubusercontent.com/91839403/150693467-c5937f39-5598-4e9a-b249-185a5d1156fc.png)

### Results
#### December (Deliverable 2)
 - Average Temperature = 71.0 deg F
 - Maximum Temperature = 83.0 deg F
 - Minimum Temperature = 56.0 deg F

![image](https://user-images.githubusercontent.com/91839403/150693611-a465a7e7-2338-475d-a801-d73874412aad.png)

### Comparison June vs. December
 Mean Temperature: June is only 3.9 Deg F warmer than December.
 Maximum Temperature: June maximum temp is only 2 Deg warmer than December
 Minimum Temperature: June Minimum Temperature is 8 Def F warmer than December
 
Comparison table:

![image](https://user-images.githubusercontent.com/91839403/150693792-10be85a5-c8bd-4e28-a6e3-d2fd9a24156d.png)

 
### Summary
The analysis of the temperature data points in June and December for Oahu, Hawaii shows consistent maximum and average temperatures for these months. aThis consistency would indicate that this location is favorable for year round surfing and support the year round operatiuon of the "Surf and Scoop" business.

Additional Queries to perform to validate this decision:
1) Additional Years: Trend and Compare June through December over several years to verify this year is not an outlier.
2) Additional Months: Look at average temperature month by month over 3-4 years and chart the data.  This would help vlaidate that June and December are the best months to use for this analysis.
3) Additional Weather: We know that precipitation is another available weather parameter.  We should query and compary days of precipitation for validate.  We could add wind to this as well.


