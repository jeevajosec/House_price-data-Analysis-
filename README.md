#House Price Analysis in Bangalore
This project aims to analyze property prices in Bangalore, focusing on the price_per_sqft (price per square foot) feature. Key analyses include exploratory data analysis, outlier detection and removal, normality checks, transformations, and correlation visualizations.

Project Steps
Q1. Basic Exploratory Data Analysis (EDA)
Perform an initial examination of the dataset, including:
Descriptive statistics for price_per_sqft and other numerical columns.
Visualization of distributions to understand central tendencies and variability.
Identification of missing values, if any.
Q2. Outlier Detection and Removal
Outliers in the price_per_sqft column are detected and removed using multiple methods. The methods applied and their respective approaches to outlier handling include:

a) Mean and Standard Deviation: Values beyond a certain number of standard deviations from the mean are treated as outliers.
b) Percentile Method: Outliers are determined by examining extreme percentiles (e.g., top and bottom 1%).
c) Interquartile Range (IQR) Method: Outliers are defined as values beyond 1.5 times the IQR above the third quartile or below the first quartile.
d) Z-Score Method: Using Z-scores, values beyond a certain threshold (typically ±3) are flagged as outliers.
For each method, outliers are handled using various strategies:

Trimming: Removing outliers.
Capping: Replacing outliers with the closest threshold values.
Imputation: Replacing outliers with the mean or median value of the column.
Q3. Outlier Removal Evaluation
A box plot of price_per_sqft is used to visualize each outlier removal method.
This helps determine which approach best normalizes the data, with minimal outliers.
Q4. Normality Check and Transformation
A histogram is used to check the normality of price_per_sqft.
Skewness and kurtosis are calculated to measure distribution symmetry and tail behavior.
If necessary, transformations are applied to normalize price_per_sqft. Common transformations include:
Log Transformation
Square Root Transformation
Cube Root Transformation
Box-Cox Transformation
Yeo-Johnson Transformation
Skewness and kurtosis are re-evaluated post-transformation to assess normality improvements.
Q5. Correlation Analysis
The correlation matrix is calculated for all numerical columns to identify relationships.
A heatmap visualizes these correlations, highlighting any strong associations.
Q6. Scatter Plot Analysis
Scatter plots are used to examine relationships between numerical variables in the dataset.
This helps identify patterns or correlations that could inform property pricing factors
