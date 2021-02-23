# Data Science Project Portfolio

This repo contains a selection of data science projects I've completed.

## Languages & Libraries:

* Python 3.6.9
* Pandas 1.1.5
* Scikit-learn
* statsmodels
* matplotlib
* seaborn

## Projects

### Communities and Violent Crime (Supervised Learning, Regression)
  * Methodically optimized OLS, Random Forest, SVM, and Gradient Boosting models of U.S. Census, FBI, and LEMAS data around 2,000 U.S. communities to predict violent crime rates via regression, prioritizing interpretability
  * Narrowed feature space from 147 to 27 by automating assessment of colinearity using Python
  * Visualized results with matplotlib and seaborn
  * Best model achieved an R^2 value of 0.6

### School Closures and COVID-19 Death Rates (Experimental Design)
  * Designed experiment using University of Oxford global COVID education policy data, UN Economic and Social Affairs data, and COVID death rates for 122 countries in April 2020
  * Established a metric for measuring strenuousness of school closure policies by country
  * Visualized results with matplotlib and seaborn
  * Tested significance of differences in death rates by strenuousness category; established that, as of several weeks into the pandemic, there was not yet a significant relationship between the choice to close schools in a country and its COVID death rate.

### Music Information Retrieval: Clustering Music Tracks by Genre (Unsupervised Learning, Classification)
  * Standardized Greek Audio Dataset, which mirrors Million-Song Dataset in structure and contains 1000 full-length musical tracks representing eight genres of Greek music
  * Visualized high-dimensional data using PCA and UMAP to gauge utility of clustering methods for classifying tracks by genre
  * Employed both full feature set and reduced feature set using PCA to optimize performance
  * Tested and tuned K-Means, Gaussian Mixture, DBSCAN, and Agglomerative Hierarchical Clustering to cluster high-dimensional audio data
