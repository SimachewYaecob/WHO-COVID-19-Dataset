Task: Data Cleaning and Preprocessing

•	Project Title: Data Cleaning for a Real-world Dataset
•	Description: Choose a dataset with missing values, duplicates, and inconsistencies. Clean the data, handle missing values, and preprocess it for analysis.
•	Dataset Reference: World Health Organization (WHO) COVID-19 Dataset


Steps followed
1. Load the Required Libraries
2. Importing Data
3. Finding and Handling Duplicate
4. Checking and Handling Missing Values
5. Handle Missing Values
6. Convert Data Types if Needed
7. Check for Inconsistencies
8. Basic Visualizations
9. Encoding Categorical Variables
10. Save Cleaned Dataset

    
Key findings and insights
1.	The Deaths column has 49,957 missing values, which is substantial and could significantly affect any mortality-related analysis. Instead of dropping this important feature, a more practical approach may be to fill the missing values with zero, assuming that the absence of reported deaths indicates no recorded fatalities. This allows for a more inclusive analysis without losing valuable data points, especially when studying trends across countries, age groups, or time periods.
2.	Deaths peaked in 2021, with the highest mortality likely driven by the widespread impact of the Delta variant and the increased strain on healthcare systems during the height of the pandemic.
3.	According to the WHO Dataset, the AMRO region recorded the highest death rate among all regions.
4.	The USA consistently reported the highest number of deaths each year, particularly between 2020 and 2022, with a noticeable peak in 2021.
5.	The data shows a clear age-related trend in COVID-19 mortality, with the highest death rates among individuals aged 65 and above. This group experienced the most severe outcomes, largely due to weakened immune systems and a higher susceptibility to serious respiratory complications.
6.	The highest number of deaths was recorded in 2021, with January of that year marking the peak month for fatalities.
