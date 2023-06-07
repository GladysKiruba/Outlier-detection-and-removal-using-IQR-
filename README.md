# Outlier-detection-and-removal-using-IQR-
Outliers are the abnormal or different from the rest of the values. This may be due to measurement error, manual error etc. These outliers affect the analysis and produce less accurate values.

What are outliers?

Outliers are the abnormal or different from the rest of the values. This may be due to measurement error, manual error etc. These outliers affect the analysis and produce less accurate values.
Outlier detection and removal and handling missing values are the most important steps in data preprocessing.

Outlier detection and removal using IQR

Any type of data can be described by five number summaries. First is arranged in ascending order then the values are calculated. 
They are the minimum value, first quartile (Q1) - it is the quarter way through the data, Median-midway through the data, third quartile (Q3) - third quarter of the data, maximum is the highest value of the data.

Interquartile range(IQR) is calculated by subtracting the first quartile from third quartile.
IQR=Q3-Q1

Interquartile range is calculated by setting the lower limit and the upper limit.
Lower limit =Q1- 1.5(IQR)
Upper limit=Q3+1.5(IQR)

So the data below the lower limit and above the upper limit are considered to be outliers.

