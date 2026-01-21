# OC-D-Portfolio
A portfolio of projects and scripts utilising Python coding
The file 'Demo_Data.xlsx' can be downloaded to run the scripts - this is basic dummy data to demonstrate the workability of the scripts in this portfolio, this data has been created for this purpose only.
The Demo_Data file represents dummy data for a weight-loss intervention with weights recorded at baseline, post-intervention and follow-up. Height at baseline is provided and BMI for each timepoint also.
Participants are alloted to one of two groups for the purpose group comparison scripts.

====
NORMALITY AND OUTLIERS SCRIPT
====
A Python script utilising Pandas, SciPy, NumPy, Matplotlib and Seaborn packages
The script automates the normality of distribution and outlier variables checks.

The Shapiro-Wilk test is used to test normality, whilst also considering Skewness, Kurtosis and mean vs. median similarity. 
Three methods of detecting outliers are employed: i. Interquartile range method using Tukey's fences, ii. Z-score and iii. Modified Z-score using the median absolute deivation. The method employed is inpart, determined by the normality of the data, and assists in detecting true outliers within the dataframe.

====
Independent Groups t-Tests
====
A Python script utilising Pandas, SciPy, NumPy, Matplotlib and Seaborn packages
The script automates normality checks and independent t-tests, conducting 6 independent tests comparing differences between groups in Weight or BMI at each time point (baseline, post-intervention, follow-up)

====
Repeated Measures ANOVA
====
A Python script utilising Pandas, SciPy, NumPy, Matplotlib and Seaborn packages
As multiple t-tests is poor practice, a 2x3-way repeated measures ANOVA script outlines the change over time within each group, group x time interaction (group at 2 levels and time at 3 levels)


