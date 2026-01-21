# OC-D-Portfolio
A portfolio of projects and scripts utilising Python coding

====
NORMALITY AND OUTLIERS SCRIPT
====
A Python script utilising Pandas, SciPy, NumPy, Matplotlib and Seaborn packages
The script automates the normality of distribution and outlier variables checks.

The Shapiro-Wilk test is used to test normality, whilst also considering Skewness, Kurtosis and mean vs. median similarity. 
Three methods of detecting outliers are employed: i. Interquartile range method using Tukey's fences, ii. Z-score and iii. Modified Z-score using the median absolute deivation. The method employed is inpart, determined by the normality of the data, and assists in detecting true outliers within the dataframe.
