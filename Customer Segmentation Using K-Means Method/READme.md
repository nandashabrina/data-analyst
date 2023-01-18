# Customer Segmentation Using K-Means Method
This folder is part of the final project for Mini Course 'Data Science' by Globy.id. Data and background are part of the question that given to do.

## Background Summary
A FMCG company is planning to release a new product. Thus, the marketing team needs customer data segmentation to determine product marketing targets. 

## Data
All the data has been collected through the loyalty cards they use to checkout. This data has been edited to be dirty data.

## Why K-Means Method?
K-Means method helps us to aggregate data points together based on certain similarities.

## Outline 

### Data Understanding
These datasets consists of 2002 rows and 11 features, include ID, Sex, Marital status, Age, Education, Income, Occupation, Height, Weight, Settlement size, and Parents name.

### Data Preprocessing
On this process carried out:
1. The deletion of the illogical data.
2. Filling up the blank on categorical field with mode.
3. Checking data duplicate.
4. Replacement of categorical into numerical value.
5. Remove unnecessary column.
6. Replacement ID as index.

### Exploratory Data Analysis
Correlation matrix is used to show the correlation coefficients between each variables (field) in the dataset of Customer's Loyalty Card.

Scatter plot to extent correlation between Age and Income.

### K-Means Implementation
There are several stages of application of the K-Means method as follows:
1. Feature scaling
2. Centroid inilization
3. Finding the value of K
4. Clustering with K-means
5. Expanding data
6. Analysis

## Conclusion
Based on the above process, it's obtained 4 cluters as follows:
1. The first cluster (segmentation 0) has relatively high income with a relatively high age span. It seems that a fairly diverse product could be marketed in this density, with appropriate functionality and quality.
2. The second cluster (segmentation 1) has a low income with a youth over the age of adults. In this cluster, a variety of products with an affordable price can be a special attraction. A special discount can be an option to attract customers.
3. The third cluster (segmentation 2) consists of low-age customers with low income. It seems suitable for age-appropriate products, of course at reasonably afford prices for young age and relatively low income.
4. The fourth cluster (segmentation 3) consists of relatively high income customers and adolescents toward adults (young adults), this cluster can be a target for a high quality product with an appropriate price.
