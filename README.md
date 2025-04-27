# YouTube Channel Prediction

This project aims to predict various metrics related to YouTube channels, including subscriber growth and total video views. The dataset used is from the [Kaggle Global YouTube Statistics 2023](https://www.kaggle.com/datasets) repository. The project involves the application of different machine learning techniques, including linear regression and random forest, to predict YouTube channel metrics.

## **Project Overview**

The primary goal of this project is to explore relationships between various metrics of YouTube channels, such as video views, uploads, subscribers, and channel categories. Based on this exploration, predictions are made for future growth in subscribers and video views.

The dataset used contains data on YouTube channels, including metrics such as:
- Total video views
- Total subscribers
- Number of uploads
- Channel categories
- Country
- Year the channel was created

## **Types of Analysis**

1. **Descriptive Analysis:**
   - Understanding past performance and providing context to current trends.
   - Examples: Correlation between total video views and subscribers, relationship between the creation year of a YouTube channel and its total subscribers.

2. **Exploratory Analysis:**
   - Delving deeper into the dataset to uncover relationships and trends.
   - Examples: Highest yearly earnings across different categories, relation between total views in the last 30 days and new subscribers gained.

3. **Prescriptive Analysis:**
   - Recommending strategies based on the insights derived from the analysis.
   - Example: Targeting content to maximize engagement based on channel category and country population.

4. **Predictive Analysis:**
   - Using statistical models and machine learning to predict future outcomes.
   - Examples: Predicting future growth in subscribers and video views based on historical data.

## **Machine Learning Algorithms Used**

1. **Linear Regression:**
   - A simple regression technique to model the relationship between input features and the target variable.
   - Used to predict subscriber growth based on the number of uploads and video views.

2. **Random Forest Regressor:**
   - A regression algorithm that uses an ensemble of decision trees to make predictions. It helps in reducing overfitting and improving prediction accuracy.

## **Key Questions Analyzed**

### **Descriptive Analysis**
1. How does the total number of subscribers correlate with the total video views across all videos on the channel?
2. What is the relationship between the year a YouTube channel was created and its total number of subscribers?

### **Exploratory Analysis**
1. How do the estimated highest yearly earnings compare across different categories of YouTube channels?
2. How do the total video views in the last 30 days relate to the number of new subscribers gained in the last 30 days for different YouTube channel types?

### **Prescriptive Analysis**
1. Based on the category of the YouTube channel, its total number of uploads, and the country's population, how can channels strategically target content to maximize engagement and subscriber growth?

### **Predictive Analysis**
1. Can we predict the future growth in subscribers for a YouTube channel based on the historical number of uploads, and total video views?
2. Based on the total number of subscribers, uploads, video views, and the category of the channel, can we predict which feature influences highest yearly earnings the most?
3. Can we predict the future growth in total video views for a YouTube channel based on its current number of subscribers, category, and uploads?
