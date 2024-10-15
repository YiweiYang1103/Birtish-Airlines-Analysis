# Birtish-Airlines-Analysis
# Flight Booking and Customer Feedback Analysis Project

## Project Summary

This project focuses on the comprehensive analysis and visualization of airline flight booking data and customer feedback data. The main goal is to understand customer booking behavior, evaluate flight route performance, and derive insights from customer reviews to help airlines optimize their services and develop business strategies. Below is an overview of the main tasks completed in the project:

### 1. Data Collection and Cleaning
- **Flight Booking Data**: Collected from internal systems.
- **Customer Reviews**: Scraped from the Skytrax website using Python's Beautiful Soup.
  - Removed special characters, stopwords, and HTML tags to clean the reviews for analysis.
- **Data Preprocessing**: Handled missing values, normalized numerical values, and split the `route` field into origin and destination airport codes.

### 2. Feature Engineering
- **Route Splitting**: Split the `route` field into origin and destination airport codes.
- **Geographical Enrichment**: Enriched each airport code with detailed geographical information (e.g., city, country, state/region).
- **Tokenization**: Tokenized customer reviews, splitting each review into individual words for subsequent text analysis.

### 3. Modeling and Analysis
- **Sentiment Analysis**: Used tools like TextBlob to evaluate customer reviews as positive or negative, adding sentiment scores to the dataset.
- **Topic Modeling**: Employed an LDA model to extract key topics from the reviews, identifying primary customer concerns regarding flight services.
- **Classification Model**: Built a Random Forest model to analyze booking behavior, identifying factors affecting booking success rates.

### 4. Tableau Visualization
- **Flight Route Map**: Created a map to display booking flows between origin and destination cities.
- **Customer Booking Behavior Dashboard**: Included charts on booking completion rates, popular routes, and customer origin cities.
- **Sentiment and Feedback Analysis**: Displayed sentiment scores, extracted key keywords from reviews, and mapped customer satisfaction alongside route performance.

### 5. Business Insights and Recommendations
- **Route Analysis**: Identified routes with high demand and high customer satisfaction, as well as routes needing improvements.
- **Service Improvements**: Suggested promoting popular add-on services to enhance customer experience and increase revenue.

## Project Deliverables
- **Cleaned Dataset**: Includes geographical information and customer sentiment analysis results, used for visualization and further analysis.
- **Visual Dashboards**: Dashboards showcasing route popularity, sentiment scores, booking success rates, and customer origins.
- **Model Analysis Report**: A report on Random Forest model analysis for optimizing customer conversion.

