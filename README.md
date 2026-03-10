# Pens and Printers Revenue Analysis

## Overview
This project cleans and validates data to help with analysis. The goal was to understand drivers of revenue and what ad campaigns to prioritize between calls, emails, or both.  

## Tools
Python, Pandas, Seaborn, scipy.stats, NumPy, PowerBI

## Dataset
The dataset contains predictors such as week, sales_method, customer_id, number sold, revenue, years_as_customer, number site visits, and state

## Methods
- Uncovered missing revenue data points and corrected through imputation of median values
- Found customer_id fields to have no returning customers and recommended
- Used one-way ANOVA testing to identify differences in revenue by customer contact methods

## Results
Found there to be a statistically significant difference in average revenue by contact method. Contact by combination of email + call was higher than just call or email. 
Calculated business metric of total Revenue per Customer by Sales Method:
- Call: $47.65
- Email: $97.01
- Email + Call: $183.80

## Files
Product Sales (Pens and Printers).pptx   - Slide deck summarizing analysis, statistical findings, and business recommendations
pens_and_printers_notebook.ipynb         - Jupyter notebook containing data cleaning, exploratory data analysis, and statistical testing
pens_and_printers_visual.pbix            - PowerBI dashboard used to visualize revenue trends by contact method and week. 

## Note
This analysis was originally developed as part of a DataCamp project and was expanded with PowerBI visuals. 
