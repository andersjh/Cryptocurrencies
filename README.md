# Cryptocurrencies

## Overview
We want to explore the idea of investing in cryptocurrencies.  However, we have no idea if there are any similarities between all the various currencies out there.  We want to identify if there are any ways we can see patterns in this emerging currency.

## Methodology

Since we don't know what our results will be in advance, we will be using unsuporvised learning techniques.

We will also be using Principal Component Analysis to reduce our featurs so we can simplify both the model and visulizations.

## Data Cleanup & Prep
- We eliminated all data that contained nulls 
- We eliminated all duplicates
- We removed all untraded currencies

## Model Cleanup & Results
- We used both MinMaxScaler and StandardScaler to improve models and visualizations
- We chose 3 items for PCA
- Using an Elbow Chart we determined that 4 clusters was our best choice.

## Next steps
- Review the clustered data to identify how these currencies are connected
- Determine if and how we might want to enter this market

