# AB testing
AB testing on E-marketing data. CTR &amp; CR analysis + Hypothesis Test

### Data Loading and Cleaning: 
Two datasets, control_group.csv and test_group.csv, are loaded. The columns are renamed for consistency, and missing values in several columns are filled with the mean values from the respective datasets.

### Descriptive Statistics: 
Basic descriptive statistics are computed for both control and test datasets, giving a general understanding of the central tendency and dispersion of the data.

### Correlation Analysis: 
Correlation matrices are generated for the numeric columns to assess the relationships between variables.

### T-Tests: 
Independent t-tests are conducted for each key metric to determine if there are statistically significant differences between the control and test groups. Metrics include the amount spent, number of impressions, reach, website clicks, number of searches, page views, added to cart, and purchases.

### Chi-Square Test: 
A chi-square test is performed to examine the relationship between the group (control or test) and the number of purchases versus clicks. The output includes the chi-square statistic and the p-value.

### Regression Analysis: 
Linear regression models are fitted to predict purchases based on website clicks for both control and test groups. A robust regression (Huber regressor) is applied to the test group data to handle outliers. The results, including coefficients and R-squared values, are summarized.
