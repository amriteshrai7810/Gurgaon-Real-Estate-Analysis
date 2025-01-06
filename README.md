# About Gurgaon Real Estate Analysis and Property Price Prediction
Developed a Streamlit-based Property Analysis Dashboard to streamline property searches in Gurgaon’s dynamic real estate market. Features include area-wise price trends, society recommendations, and personalized price predictions. Leveraging data from 3,000+ web-scraped listings, the dashboard reduces search time by 30%, enabling quicker, informed decisions for buyers and investors.

# Video Demo on LinkedIn
LinkedIn Link: [linkedin.com](https://www.linkedin.com/feed/update/urn:li:activity:7171491581231902721/)



# Description

## Features of Dashboard

- Data Exploration: Analyzed 3,800+ property data points, including location, price, room types, and amenities. Categorized properties into minimal, semi-luxurious, and luxurious types.
- Location and Price Insights: Mapped geo data, explored price trends by area, and analyzed flat distribution (2BHK, 3BHK) with corresponding price ranges.
- Price Prediction: Developed a Random Forest Regressor to predict property prices based on selected features, offering users price expectations.
- Society Recommendation: Built a recommendation system based on proximity to key locations like hospitals and malls to help users find similar societies.
- Web Scraping: Used BeautifulSoup and requests to dynamically scrape property data for analysis and recommendations.

## Steps

- Data Scraping: Extracted 3,000+ property listings from 99acres and Magic Bricks using Selenium and Beautiful Soup.
- Data Cleaning: Used NumPy and Pandas for missing value imputation, outlier removal, feature engineering, and transformations.
- Analysis: Created visualizations (map plot, box plot, scatter plot) to explore price trends, property sizes, and area-wise prices.
- Machine Learning: Built a price prediction model with a 90% prediction interval for selected amenities.
- Recommendation System: Suggested societies based on landmarks and apartments within those societies.
- Deployment: Launched the Streamlit dashboard on Amazon EC2 for real-time use.
