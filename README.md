# Airline Analytics Project

## Overview
This repository contains the final project for the ADSP 31013 "Big Data Platforms" class at the University of Chicago. The project aims to address various challenges in the airline industry through data-driven analytics and machine learning techniques. The entire analysis is conducted in a big data environment, leveraging Google Cloud Storage for data storage and a PySpark cluster for processing.

## Team Members
- Kshitiz Sahay
- Xiomara Flores
- Yijing Sun
- Robert Surridge

## Project Objectives and Solutions

### Flight Price Prediction and Optimization (1 person)
**Problem:** Predict and optimize ticket prices to maximize revenue and occupancy.  
**Solution:** Use regression models to predict ticket prices based on historical data, considering factors like travel duration, elapsed days, flight type (non-stop or not), and total travel distance. Implement dynamic pricing strategies to optimize revenue and seat occupancy.  
**Techniques:** Regression, time series analysis, pricing optimization.

### Customer Segmentation and Personalized Recommendations (1 person)
**Problem:** Segment customers based on their preferences and provide personalized flight recommendations.  
**Solution:** Apply classification and recommendation systems to cluster customers into different segments based on their preferences (e.g., basic economy, refundable tickets, non-stop flights) and recommend flights that match their preferences.  
**Techniques:** Classification, clustering, collaborative filtering, NLP for customer reviews and preferences.

### Route and Aircraft Optimization (2 people)
**Problem:** Optimize routes, aircraft allocation, and seat inventory for maximum efficiency and profitability.  
**Solution:** Utilize association analysis to discover patterns in historical flight data to determine which routes are often booked together and analyze seat occupancy patterns. Optimize route planning, aircraft allocation, and cabin configurations based on these insights.  
**Techniques:** Association rule mining, clustering, capacity planning, and allocation optimization.

## Getting Started
1. Clone this repository: `git clone https://github.com/YOUR-USERNAME/airline_analytics.git`
2. Ensure you have access to the Google Cloud Storage bucket where the data is stored.
3. Set up a PySpark cluster on Google Cloud Platform.
