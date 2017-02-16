# Clustering Purchasing Patterns for Wholesale Customers

This project is the final project for Udacity's Machine Learning Nanodegree course on unsupervised learning. Unsupervised learning involves finding patterns in unlabelled data. Essentially, unsupervised learning algorithms work by clustering data points based on a metric for determining similarity. The data come from a wholesale food distributor, with features detailing the amount of each type of food (fresh, frozen, dairy, etc.) purchased by each customer over a one-year period. The goal of this project is to apply unsupervised learning to customers' purchases to find a relationship between customers, and to think about how this relationship can be used to maximize business.

## Analysis

The analysis proceeds as follows:
- Data Exploration - statistics and feature visualizations
- Data Preprocessing - feature scaling, outlier detection
- Feature Transformation - principal component analysis, dimensionality reduction
- Clustering - KMeans, tSNE visualization

## Technologies

This project was completed using Python 2.7. Libraries include:
- scikit-learn
- pandas
- numpy
- matplotlib/seaborn

## Results

After applying KMeans clustering to the transformed data, two distinct groups of data points become clear. Customers purchasing greater amounts of fresh and frozen foods were identified as hotels and restaurants, whereas customers purchasing greater amounts of dairy, grocery, deli, and detergents were retailers. 

The wholesaler is said to be looking for a way to modify its delivery schedule. With the analysis complete, one option would be to A/B test a change in the delivery schedule. For example, we could try delivering in the morning for some hotels and restuarants, and in the afternoon for some retailers, and survey the customers on how they like the change. This has the potential to be a profitable change, not only for the wholesaler but for the customers. 
