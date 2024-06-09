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
- Amalgamated and refined data from SeatGeek and Ticketmaster to enhance fan profiling and improve data quality.
- Scripts: [data_integration.py](scripts/data_integration.py), [data_cleansing.py](scripts/data_cleansing.py)

## Advanced Predictive Analytics
- Developed a linear regression model to predict ticket prices, enabling dynamic pricing strategies.
- Model achieved a high R-squared value of 0.9019, indicating strong predictive power.
- Notebook: [machine_learning.ipynb](notebooks/machine_learning.ipynb)

## Clustering for Fan Segmentation
- Utilized KMeans clustering to segment fans based on purchase behavior, ticket prices, and engagement metrics.
- Informed targeted marketing strategies.
- Notebook: [clustering.ipynb](notebooks/clustering.ipynb)

## Real-Time Engagement and Upgrades
- Implemented strategies to offer real-time seat upgrades and personalized in-app notifications to enhance fan experience and maximize revenue.
- Script: [real_time_engagement.py](scripts/real_time_engagement.py)

## Revenue Optimization
- Compared predicted ticket prices with actual prices to identify potential revenue increases.
- On average, the model increased revenue by $9.12 per ticket, projecting a significant revenue boost for a sold-out stadium.
- Notebook: [revenue_optimization.ipynb](notebooks/revenue_optimization.ipynb)

## Visualization and Reporting
- Generated visual representations of model performance and cluster analysis to facilitate data-driven decision-making and strategic planning.
- Notebooks and visualizations included in the project.

## Technologies Used
- **Programming Languages:** Python, PySpark, SQL
- **Data Visualization:** Power BI, Tableau
- **Cloud Infrastructure:** Amazon AWS
- **Machine Learning:** Linear Regression, KMeans Clustering

## Usage
1. Navigate to the `notebooks` directory to explore the Jupyter notebooks.
2. Run the scripts in the `scripts` directory to process data and generate predictions.
3. Visualize the results using the provided visualization tools.

## Project Structure
- **data/**: Contains the raw data files.
- **notebooks/**: Jupyter notebooks for data processing, machine learning, and analysis.
- **scripts/**: Python scripts for data integration, cleansing, predictive modeling, and clustering.

## Contact
For any questions or suggestions, please reach out to Anurag Vedagiri at anurag.vedagiri@gmail.com.

