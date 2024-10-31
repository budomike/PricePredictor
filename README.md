# Housing Price Prediction Model


This Python program implements a predictive model for housing prices based on various features such as square footage, number of bedrooms and bathrooms, neighborhood, and year built. The model utilizes the scikit-learn library for data preprocessing, model training, and prediction. 


Key features of the program include:

1. Data Preprocessing: The dataset is preprocessed to handle categorical variables, remove outliers, and standardize numerical features.

2. Model Training: A Linear Regression model is trained using a pipeline, which combines preprocessing steps and model fitting for efficient processing.

3. Prediction Functionality: Users can make predictions for house prices by inputting relevant features, such as square footage, bedrooms, bathrooms, neighborhood, and year built.

This program serves as a practical example of applying machine learning techniques to real-world datasets.

## Price Example
![pricing_example](https://i.imgur.com/0lr4DZQ.png)

## Correlation Heatmap
The correlation heatmap provides a visual representation of the correlation between different features in the dataset. The heatmap shows a strong correlation between the square feet and the dependent variable of our application: the price.

![correlation_heatmap](https://i.imgur.com/WKcIfzJ.png)

## Outlier Detection
The outliers detection visualization includes boxplots for various features, highlighting the presence of outliers and demonstrating the impact of removing outliers on the dataset.

![outlier_charts](https://i.imgur.com/j96tUFs.png)
