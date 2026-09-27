# Chicago Crime Analysis (2001 - 2024)
## Business Objective
* The primary objective of this project is to analyze the raw Chicago Crime dataset to uncover temporal and spatial crime patterns. The workflow involves comprehensive data cleaning in Python, followed by data modeling and the development of a 2-page interactive executive dashboard in Power BI to drive data-informed decisions.

## Tech Stack Used
* Python (Pandas): Data extraction, transformation, handling missing values, and data type formatting.

* Power BI: Data modeling, DAX calculations, and interactive data visualization.

## Key Insights
* Crime Trends Over Time: Crime volume peaked significantly during the periods of Jan-Oct 2001 and Sep 2023-May 2024.

* Peak Crime Hours: Crime incidents are highly concentrated between the afternoon and late evening hours (12:00 PM to 10:00 PM).

* Top Crime Locations: 'Street' environments are the most vulnerable locations for criminal activities.

* Ward-Wise Crime Rate: Ward 27 recorded the highest number of reported crimes across the district.

* Arrest Efficiency: The overall arrest rate is notably low, with only 23.9% of cases resulting in an arrest, while 76.1% remain unarrested.

* Domestic vs. Non-Domestic: General (non-domestic) crimes dominate the dataset at 83%, whereas domestic incidents account for 17% of total cases.

## How to Run this Project

* Download the raw Chicago Crime dataset from the official portal and place it in the project root directory.

* Run the crimes.ipynb Jupyter Notebook to execute the data cleaning pipeline and generate the Cleaned_Chicago_Crime.csv file locally.

* Open Chicago_Crime_Dashboard.pbix in Power BI and refresh the data source to view the visualizations.