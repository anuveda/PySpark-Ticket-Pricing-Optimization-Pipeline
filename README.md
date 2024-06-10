# PySpark Ticket Pricing Optimization Pipeline

## Project Overview
Implemented a PySpark-based data processing and machine learning pipeline to analyze and predict ticket prices for sports events using data from SeatGeek and Ticketmaster. Emphasized data integration, cleansing, linear regression for predictive analytics, clustering for fan segmentation, real-time engagement strategies, revenue optimization, and visualization for strategic planning and decision-making.

## Table of Contents
1. [Data Integration and Cleansing](#data-integration-and-cleansing)
2. [Advanced Predictive Analytics](#advanced-predictive-analytics)
3. [Clustering for Fan Segmentation](#clustering-for-fan-segmentation)
4. [Real-Time Engagement and Upgrades](#real-time-engagement-and-upgrades)
5. [Revenue Optimization](#revenue-optimization)
6. [Visualization and Reporting](#visualization-and-reporting)
7. [Technologies Used](#technologies-used)
8. [Setup and Installation](#setup-and-installation)
9. [Usage](#usage)
10. [Project Structure](#project-structure)
11. [Contact](#contact)

## Data Integration and Cleansing
- Integrated and refined over 100,000 records from SeatGeek and Ticketmaster.
- Applied data cleaning techniques to handle missing values and normalize features, improving data quality and consistency.

## Advanced Predictive Analytics
- Developed a linear regression model to predict ticket prices, achieving an R-squared value of 0.9019, indicating strong predictive power.
- Model evaluation metrics: RMSE of 127.58 and MAE of 39.95, demonstrating high accuracy.

## Clustering for Fan Segmentation
- Utilized KMeans clustering to segment fans into 5 clusters based on purchase behavior, ticket prices, and engagement metrics.
- Identified high-engagement fans with total ticket prices ranging from $1971.5 to $10708.65.

## Real-Time Engagement and Upgrades
- Implemented strategies to offer real-time seat upgrades and personalized in-app notifications, enhancing fan experience and maximizing revenue.
- Real-time seat upgrades for fans with deal scores > 7, resulting in premium seat offers and increased engagement.

## Revenue Optimization
- Compared predicted ticket prices with actual prices to identify potential revenue increases.
- On average, the model increased revenue by $9.12 per ticket, projecting a total additional revenue of $196,500 for a sold-out stadium (21,550 seats).

## Visualization and Reporting
- Generated visual representations of model performance and cluster analysis to facilitate data-driven decision-making and strategic planning.
- Created interactive dashboards and visualizations using Power BI and Tableau to present insights to stakeholders.
- Notebooks and visualizations included in the project.

## Technologies Used
- **Programming Languages:** Python, PySpark, SQL
- **Data Visualization:** Power BI, Tableau
- **Cloud Infrastructure:** Amazon AWS
- **Machine Learning:** Linear Regression, KMeans Clustering

## Usage
1. Load the cleaned dataset using the provided notebook.
2. Train the linear regression model and evaluate its performance.
3. Apply KMeans clustering to segment the fan base.
4. Visualize the results and generate reports.
