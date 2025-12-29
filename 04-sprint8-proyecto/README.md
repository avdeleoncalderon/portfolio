# Sprint 8 Zuber: Rideshare Patterns & Environmental Impact Analysis

## Description
A data-driven study of Chicago's rideshare market. I performed web scraping for weather data, executed advanced SQL queries to analyze competitor behavior, and conducted statistical hypothesis testing to measure the impact of weather conditions on trip durations.

### **Key Insights**

- **Market Landscape:** Analyzed over 60 taxi companies to identify market leaders (like Flash Cab) and seasonal trends during November 2017.
- **Geospatial Trends:** Identified the top 10 drop-off neighborhoods, highlighting high-demand urban hubs like the *Loop*.
- **Weather Segmentation:** Integrated weather records with trip data to categorize rides into "Good" and "Bad" conditions based on rainfall and storms.

### **Hypothesis Testing (Weather Impact)**

I tested the hypothesis: *"The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."*

- **Methodology:** Conducted an independent samples T-test to compare travel times.
- **Findings:** The data confirmed a statistically significant difference in trip durations during adverse weather, providing critical evidence for Zuber to optimize dynamic pricing and ETAs.

## Main file
- [notebook.ipynb](notebook.ipynb)
