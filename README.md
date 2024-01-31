# Google Play Store Apps and Reviews Analysis

## Overview

Mobile apps are a ubiquitous part of our digital landscape. This project involves a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. The analysis delves into various aspects, including app categories, ratings, sizes, prices, and user reviews. The goal is to derive insights that can inform strategies for driving growth and retention in the highly competitive app market.

## Dataset

The dataset consists of two files:

- **apps.csv:** Contains details of the applications on Google Play, with 13 features describing each app.
- **user_reviews.csv:** Contains 100 reviews for each app, pre-processed and attributed with sentiment analysis features.

## Analysis Steps

### 1. Data Cleaning

Data cleaning is a crucial step to ensure accurate analysis. Special characters in the `Installs` and `Price` columns were removed to make them purely numeric. A summary of the cleaned dataset was provided.

### 2. Correcting Data Types

Converted `Installs` and `Price` columns to the float data type for numeric calculations.

### 3. Exploring App Categories

Explored the distribution of apps across different categories, identifying the categories with the highest and lowest prevalence in the market.

### 4. Distribution of App Ratings

Analyzed the distribution of app ratings, providing insights into the average rating and the overall distribution of ratings in the dataset.

### 5. Size and Price of an App

Explored the relationship between app size and ratings, as well as the distribution of app prices. Investigated how these factors might influence user preferences.

### 6. Relation Between App Category and App Price

Examined the pricing trends across different app categories, highlighting the categories with the highest and lowest prices.

### 7. Filter Out "Junk" Apps

Identified and filtered out potentially irrelevant or "junk" apps with extreme prices, providing a more accurate representation of app pricing trends.

### 8. Popularity of Paid Apps vs Free Apps

Investigated the number of downloads for paid and free apps, revealing insights into the user preference for app pricing.

### 9. Sentiment Analysis of User Reviews

Performed sentiment analysis on user reviews, comparing the sentiment polarity of reviews for paid and free apps.

## Code Structure

- [apps_and_reviews_analysis.ipynb](notebooks/apps_and_reviews_analysis.ipynb): Jupyter Notebook containing the main analysis code.
- [datasets/apps.csv](datasets/apps.csv): Dataset containing details of Google Play apps.
- [datasets/user_reviews.csv](datasets/user_reviews.csv): Dataset containing user reviews for apps.
- [LICENSE](LICENSE): License information for the project.
