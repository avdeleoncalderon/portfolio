# Sprint 6 Predictive Market Analysis: Success Strategies in the Video Game Industry

## Description
A comprehensive analysis of historical sales data and reviews to forecast 2017 market trends. This project identifies profitable platforms and genres through statistical analysis and hypothesis testing, optimizing global advertising campaign planning.

## **The Challenge (Context)**

The online store *Ice* needed to optimize its advertising investments for 2017. The objective was to analyze sales data, expert ratings, and ESRB ratings to discover which factors determine a video game's commercial success across different global regions.

### **Tech Stack**

- **Language:** Python
- **Libraries:** Pandas (Data Cleaning), NumPy (Calculations), Matplotlib & Seaborn (Visualization), SciPy (Statistics).
- **Tools:** Jupyter Notebook.

### **Key Insights**

- **Platform Lifecycle:** I identified that gaming consoles have an average lifecycle of 10 years. The data suggested that PS4 and Xbox One were the safest bets for 2017, while legacy consoles like PS3 and X360 were in decline.
- **The Power of Reviews:** Using scatter plots and correlation analysis, I determined that professional critic scores have a significantly stronger impact on sales than user reviews.
- **Regional Differences:** I discovered that the Japanese (JP) market favors handheld consoles (3DS) and the Role-Playing genre, contrasting with North America (NA) and Europe (EU), where Shooters and home consoles dominate.

### **Statistical Hypothesis Testing**

I formulated and tested two key hypotheses using T-tests:

1. **Platforms:** I confirmed that average user ratings between Xbox One and PC platforms are similar.
2. **Genres:** I proved a significant difference in user ratings between the Action and Sports genres.

### **Business Conclusion & Recommendations**

For the 2017 strategy, marketing budgets should be concentrated on **PS4** titles within the **Shooter** genre for Western markets. Conversely, for the Asian market, the priority remains the **Nintendo 3DS**. High-risk, high-reward genres like Action and Sports should be handled with specific regional preferences in mind.

## Main file:  
- [notebook.ipynb](notebook.ipynb)
