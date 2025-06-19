# Global-Earthquake-Patterns

PROJECT OVERVIEW :

Global Earthquake Patterns: In this project I used 30 days of earthquake data to create a simple dashboard. It includes a world map showing earthquake locations and magnitudes, a list of the top 10 strongest earthquakes, and the percentage of earthquakes in each main region. It also shows, for each smaller location, how many earthquakes happened and their average and maximum magnitudes. Everything is connected to one date filter so we can see changes day by day.(https://public.tableau.com/app/profile/ashna.m4135/viz/Book1_17501844028490/GlobalEarthquakeTracker?publish=yes )

![image](https://github.com/user-attachments/assets/268ba17c-c68c-4579-b282-00d288eb44b0)



DATA OVERVIEW:
This dataset provides an overview of global earthquake events, including the date, time, location coordinates (latitude and longitude), magnitude, and geographical classification (specific location and broader region). Each record represents an individual earthquake, with unique IDs and timestamps. The dataset can be used to visualize earthquake patterns on a map, identify the strongest events, analyze regional distributions, and calculate average and maximum magnitudes by location. Notably, one magnitude value (36) appears to be an outlier and may require further validation or cleaning.



![image](https://github.com/user-attachments/assets/0c5be3ca-18f9-4168-9800-0160c6e04ecf)


ANALYSIS:

This Tableau dashboard titled "Global Earthquake Tracker" provides a visual summary of recent global earthquakes. It includes:
  >>An interactive world map showing earthquake locations by magnitude
  >>A bar chart or table highlighting the top 10 biggest earthquakes
  >>A regional distribution chart, showing how many quakes occurred in each broad location
  >>Detailed stats per location: total quakes, average and max magnitude


STEP BY STEP process:

1. Interactive Map View
    >>Points represent individual earthquakes, plotted by latitude and longitude.
    >>Circle size indicates magnitude (larger circles = stronger quakes).
    >>Colour or tooltip details often include date, time, magnitude, and location.

2. Magnitude Distribution
   >>its Often shown as a bar chart or histogram. 
   >>Displays how many earthquakes fall into each magnitude range (e.g., 0–3, 3–6, 6–9+)

3. Time Series Trends
   >>A line or area chart over time showing earthquake frequency or cumulative energy release.
   >>What to look for: Are there periods with unusually high activity? Spikes may correlate with tectonic events or aftershock sequences.


4. Top Events or Table of Largest Quakes
   >>A table listing the strongest earthquakes (by magnitude), with their details.
   >>Useing this to highlight key events during the period and compare their locations and impact


SUMMARY IN Q/A:

Q1: How can this dashboard help in disaster risk management?
A: By identifying high-frequency earthquake zones and peak magnitude events, authorities can prioritize early warning systems, infrastructure reinforcement, and emergency planning in vulnerable regions.

Q2: What were the limitations of your data?
A: The dataset covers only a limited time window (e.g., 30 days), so findings reflect short-term patterns. Broader insights require a larger historical dataset.

Q3: What techniques could be applied for further pattern discovery?
A: Clustering algorithms like DBSCAN or K-Means could group earthquakes spatially to uncover hidden seismic zones or aftershock sequences.

Q4: How would you apply machine learning to this dataset?
A: A supervised model could be trained to classify earthquake severity, while time series models (e.g., ARIMA, LSTM) could forecast future frequency trends in high-risk zones.

Q5: How would you scale this project with real-time data?
A: Integrate live earthquake feeds from sources like the USGS API, automate data ingestion with Python or Kafka, and refresh Tableau dashboards via scheduled updates to support real-time monitoring.


