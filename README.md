# Airline Dashboard Project

## Overview

This project aims to create a comprehensive Airline Dashboard using Power BI to analyze various aspects of airline operations and passenger demographics. The dashboard provides insights into passenger numbers, demographic trends, and flight statuses over time.

## Dataset

The dataset contains the following columns:
- **Passenger ID**: Unique identifier for each passenger
- **First Name**: Passenger's first name
- **Last Name**: Passenger's last name
- **Gender**: Passenger's gender
- **Age**: Passenger's age
- **Nationality**: Passenger's nationality
- **Airport Name**: Name of the airport
- **Airport Country Code**: Country code of the airport
- **Country Name**: Name of the country
- **Airport Continent**: Continent where the airport is located
- **Continents**: Continent data for analysis
- **Departure Date**: Date of departure
- **Arrival Airport**: Destination airport
- **Pilot Name**: Name of the pilot
- **Flight Status**: Status of the flight

## Analysis and Visualizations

The dashboard includes several key visualizations and analyses to provide insights into the data:

### Passenger Demographics
1. **What is the gender distribution of passengers?**
   - **Visualization Type**: Pie Chart or Bar Chart
   - **Answer**: The visualization displays the percentage of male and female passengers.

2. **What is the age distribution of passengers?**
   - **Visualization Type**: Histogram or Bar Chart
   - **Answer**: The visualization shows the distribution of passenger ages.

3. **What are the top nationalities of passengers?**
   - **Visualization Type**: Bar Chart
   - **Answer**: The visualization lists the most common nationalities among passengers.

### Flight Operations
4. **What is the distribution of flights by airport continent?**
   - **Visualization Type**: Pie Chart or Bar Chart
   - **Answer**: The visualization displays the number of flights departing from each continent.

5. **What is the flight status breakdown (e.g., on-time, delayed, cancelled)?**
   - **Visualization Type**: Pie Chart or Bar Chart
   - **Answer**: The visualization shows the percentage of flights by status.

6. **Which airports have the highest number of departures?**
   - **Visualization Type**: Bar Chart
   - **Answer**: The visualization displays the airports with the most departing flights.

7. **How do the number of departures vary by departure date?**
   - **Visualization Type**: Line Chart or Bar Chart
   - **Answer**: The visualization shows the trend of departures over time.

### Pilot and Crew Analysis
8. **Who are the most frequently assigned pilots?**
   - **Visualization Type**: Bar Chart
   - **Answer**: The visualization lists the pilots with the most flights.

9. **What is the flight status breakdown for each pilot?**
   - **Visualization Type**: Stacked Bar Chart
   - **Answer**: The visualization shows the flight status distribution for each pilot.

### Geographic Insights
10. **Which countries have the highest number of departing passengers?** (using DAX)
    - **Visualization Type**: Map
    - **Answer**: The visualization displays the number of departing passengers from each country on a world map.

11. **Which arrival airports are the most common destinations?**
    - **Visualization Type**: Bar Chart
    - **Answer**: The visualization lists the most common arrival airports.

### Performance Metrics
12. **What is the average age of passengers by flight status?**
    - **Visualization Type**: Bar Chart or Line Chart
    - **Answer**: The visualization shows the average age of passengers for each flight status.

13. **What is the gender distribution by flight status?**
    - **Visualization Type**: Stacked Bar Chart
    - **Answer**: The visualization shows the gender distribution for each flight status.

14. **How does the number of departures vary by continent?**
    - **Visualization Type**: Bar Chart
    - **Answer**: The visualization displays the number of departures from each continent.

### Seasonal and Temporal Analysis
15. **How do passenger demographics (age, gender, nationality) change over time?**
    - **Visualization Type**: Line Chart or Bar Chart
    - **Answer**: The visualization shows how passenger demographics change over time.

16. **What is the monthly trend of flight statuses?**
    - **Visualization Type**: Line Chart
    - **Answer**: The visualization shows the monthly trend of flight statuses.

## DAX Functions

This project utilizes DAX (Data Analysis Expressions) functions to perform various calculations and aggregations within the Power BI dashboard. DAX functions are applied to the `Age`, `Gender`, `Nationality`, and `Passenger ID` columns. These functions calculate average ages, count passengers by gender and nationality, and determine the number of passengers by country. The use of DAX enables dynamic and interactive analysis, providing deeper insights into the dataset and enhancing the overall functionality of the dashboard.

## Conclusion
The Airline Dashboard provides valuable insights into airline operations and passenger demographics. By using Power BI's powerful visualization tools and DAX functions, we can effectively analyze and present data trends over time.
