# Airbnb Insights: A Comparative Analysis of Chicago and New Orleans

### Project Overview

This project provides a comparative analysis of Airbnb markets in Chicago and New Orleans. It aims to reveal the factors that influence pricing, property types, and hosting behaviors. Data from Inside Airbnb is used to offer insights for hosts, guests, and urban planners.

### Problem Statement

The main goal is to identify and compare the key factors that determine Airbnb listing prices, availability, and host characteristics in Chicago and New Orleans. Understanding these differences can inform decisions for Airbnb hosts, help guests make better booking choices, and provide insights into urban tourism trends.

### Data Sources

The analysis uses publicly available Airbnb datasets for Chicago and New Orleans, likely from [Inside Airbnb](http://insideairbnb.com/get-the-data.html).

### Methodology

The project workflow includes these key steps:

*   **Data Retrieval:** Acquiring the Airbnb datasets for both cities.
*   **Data Cleaning and Preparation:** Handling missing values, duplicates, and converting data types for accurate analysis and visualization.
*   **Exploratory Data Analysis (EDA):** Performing univariate, bivariate, and multivariate analysis to understand data distributions, relationships, and patterns within each city's dataset.
*   **Feature Engineering:** Creating new features or transforming existing ones, if needed, to enhance the analysis (e.g., price per person).
*   **Insights Generation:** Exploring trends in pricing, property characteristics, availability, and host behaviors across the two cities.
*   **Visualization:** Creating interactive visualizations and dashboards to illustrate key findings.

### Insights

The analysis yielded the following insights:

#### Overview

*   **Market Size and Density:** A comparison of the number of listings and their distribution across different neighborhoods in Chicago and New Orleans.
*   **Property Type Prevalence:** Identifying the dominant property and room types in each city's Airbnb market (e.g., entire homes/apartments vs. private rooms).
*   **Listing Availability:** Investigating patterns and trends in listing availability, possibly revealing seasonal fluctuations or high-demand periods.
   <img width="1300" height="740" alt="Overview-Chicago" src="https://github.com/user-attachments/assets/c6c23203-1289-4480-91b4-6b1f4bc474ed" />


#### Property

*   **Property Features and Pricing:** Examining the correlation between property features (number of bedrooms, bathrooms, amenities) and listing prices in each city.
*   **Property Type Impact on Price:** Analyzing how different property types (e.g., entire home, private room, shared room) affect listing price distributions.
*   **Minimum/Maximum Stays:** Understanding stay duration patterns and their influence on booking strategies.
  <img width="1300" height="740" alt="Property-New_Orleans" src="https://github.com/user-attachments/assets/14c14102-8eeb-4acf-97e7-6f89e66c3246" />


#### Price

*   **Neighborhood-Based Price Variation:** Identifying the neighborhoods with the highest and lowest average listing prices in each city.
*   **Seasonal Pricing Trends:** Analyzing price fluctuations across different seasons to identify peak and off-peak periods.
*   **Factors Influencing Price:** Determining the key factors (location, property type, amenities, reviews) that most significantly impact listing prices in Chicago and New Orleans.
  <img width="1300" height="740" alt="Price-Chicago" src="https://github.com/user-attachments/assets/85c9408d-5d44-4904-b2e9-5a500362a1ea" />


#### Hosting

*   **Host Response Metrics:** Investigating host response times and rates, and their relationship with reviews and overall guest experience.
*   **Host Listing Concentration:** Exploring the distribution of listings among individual hosts and potential professional hosting services.
*   **Host Profile Analysis:** Studying the characteristics of hosts (e.g., superhost status) and their influence on listing performance.
  <img width="1300" height="740" alt="Hosting-Chicago" src="https://github.com/user-attachments/assets/fa9e3d84-e1bb-46e8-98b5-3a284c2f901e" />


#### Tools and Technologies

*   **Programming Language:** Python
*   **Libraries:** Pandas, Numpy
*   **Visualization Tools:** Power BI (for interactive dashboards)
