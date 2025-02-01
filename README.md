# Hotel Booking Data Analysis

Welcome to my Hotel Booking Data Analysis project. In this project I dove into hotel booking data by cleaning it up, exploring it, and extracting actionable insights using Python and Pandas. This repo captures everything from data cleaning to EDA, all in a style that’s straightforward and hands-on.

# Project Overview

This project focuses on understanding various aspects of hotel bookings. I worked with multiple CSV files containing data on dates, hotels, rooms, and bookings. My analysis covers everything from cleaning raw data, removing outliers using statistical methods to visualizing trends and distributions using a mix of Python libraries.

# Data

The analysis is based on the following CSV files:

1. dim_date: Contains dates, week numbers, and day type information.
2. dim_hotels: Details of hotel properties like IDs, names, categories, and cities.
3. dim_rooms: Information on room types and classes.
4. fact_aggregated_bookings: Summary data with successful bookings and capacity per room type.
5. fact_bookings: Detailed booking records including booking status, check-in/out dates, guest counts, and revenue.

# Tech Stack

1. Python: The programming language for data analysis.
2. Pandas: For data manipulation and cleaning.
3. Matplotlib & Seaborn: For creating visualizations.
4. Jupyter Notebook: The environment used for developing and sharing the analysis.

# Data Cleaning

I started by getting the data into shape, making sure it was analysis-ready. Here’s a quick rundown of the cleaning steps I took:

1. Date Conversions: Converted various date columns into proper datetime objects for accurate time-based analysis.
2. Handling Missing Values: Identified and filled missing values where appropriate, ensuring that gaps in the data wouldn’t skew the analysis.
3. Outlier Removal: Applied outlier detection using the Z-score method and the 3-sigma rule to remove data points that were too far from the mean. This helped in reducing noise and improving the reliability of 
   subsequent analyses.
4. Feature Engineering: Derived new metrics such as booking lead time (days between booking and check-in) and stay duration (check-out date minus check-in date) to enrich the dataset for further analysis.

# Exploratory Data Analysis (EDA)

Once the data was cleaned, I jumped into EDA to uncover trends and patterns:

1. Trend Analysis: Used line plots to track booking trends over time and identify seasonal patterns.
2. Distribution Analysis: Created boxplots and horizontal bar charts to compare metrics like occupancy rates and guest counts across different categories.
3. Categorical Insights: Leveraged heatmaps to visualize the distribution of booking statuses (Checked Out, Cancelled, No Show) across various booking platforms.
4. Correlation Studies: Explored relationships between key variables—like examining whether longer booking lead times are associated with higher cancellation rates or if longer stays correlate with higher guest   
   ratings.
5. Visual Storytelling: Combined various visualizations to present the data in a way that’s both informative and easy to understand, making the insights accessible at a glance.

# Insights Generated.

1. Occupancy rate for Business and Luxury category is 58.2% and 57.7% respectively.
2. RoomType 2 has highest bookings of 49484 and RoomType4 has lowest bookings of 16602.
3. Both the hotel category Business and Luxury sees higher bookings in Weekday as compared to Weekend.
4. Hotel AtliQ Blu has operated 37 times in full occupancy and AtliQ Palace has operated 10 times in full occupancy which is lowest.
5. Across every hotel revenue realized is between 85 - 90 % of the revenue genrated.
6. AtliQ Palace has the highest revenue leakeage of 52.83M due to cancellations.
7. The average booking lead time for Luxury and Business category is 2 and 4 days respectively.
8. AtliQ Blue hotel has highest average rating of 3.8 and AtliQ Seasons hotel has lowest average rating of 3.1.


