# Sprint 5 Telecom Revenue Optimization: Megaline User Behavior Study

## Description
A data-driven analysis of user behavior and profitability for Megaline's prepaid plans. By merging multiple datasets and performing T-tests, I identified revenue drivers and validated hypotheses regarding regional spending and plan performance to guide marketing budget allocation.

## **Business Objective**

Megaline's commercial department sought to adjust its advertising budget. My task was to determine which of the two plans generates higher average revenue and whether the users' geographic location influences spending behavior.

### **Tech Stack**

- **Language:** Python
- **Libraries:** Pandas (Multi-database manipulation), Matplotlib/Seaborn (Visualization), SciPy (Statistical testing).
- **Techniques:** Data Merging, Data Aggregation, Outlier Cleaning, and Hypothesis Testing.

### **Key Insights**

- **Data Consolidation:** I merged call, message, and internet usage logs into a unified monthly dataframe per user to ensure precise revenue calculation.
- **Consumption Patterns:** Although the 'Surf' plan has a lower base cost ($20), users frequently exceed data limits, leading to high variable revenue from surcharges.
- **Data Storytelling:** 'Ultimate' plan users rarely exceed their limits, providing the company with stable but fixed monthly income.

### **Hypothesis Testing (Inferential Statistics)**

I applied **independent samples t-tests** to validate two critical theories:

1. **Revenue Disparity:** Does one plan truly earn more than the other? (Result: Average revenue differs significantly).
2. **Regional Effect:** Do users in the NY-NJ area spend more than those in other regions? (Comparative analysis of regional means).

## Main file:
- [notebook.ipynb](notebook.ipynb)
