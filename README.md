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

## Results

### June
The following Query retrieves June temperatures

![image](https://user-images.githubusercontent.com/91839403/151634656-dfb7f2e4-92b8-47da-86c0-dc429fc96e39.png)

The June temperature data is then converted to a list

![image](https://user-images.githubusercontent.com/91839403/151634769-371e659f-6a36-4916-8018-c65ecba0c67a.png)

The June data is then converted to a data frame

![image](https://user-images.githubusercontent.com/91839403/151634826-d9139778-ade1-405e-9497-f7b1a0f8ae27.png)







#### June (Deliverable 1)
 - Average Temperature = 74.9 deg F
 - Maximum Temperature = 85.0 deg F
 - Minimum Temperature = 64.0 deg F


![image](https://user-images.githubusercontent.com/91839403/150693467-c5937f39-5598-4e9a-b249-185a5d1156fc.png)

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
1) Additional Years: Trend and Compare June average Temperature over multiple years to validate results.  The data below shows the average temperature in June is consistent over several years and does support the business over time in June

![image](https://user-images.githubusercontent.com/91839403/151636128-813f92e1-3111-42d4-9d82-7c7b2d2b890b.png)



1) Additional Years: Trend and Compare December average Temperature over multiple years to validate results.  The data below shows the average temperature in December is also consistent over several years and does support the business over time in December

![image](https://user-images.githubusercontent.com/91839403/151635898-b9d180ed-17cd-4482-8f3b-4a1a93c3c2b7.png)

