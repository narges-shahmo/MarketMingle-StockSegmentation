# MarketMingle: Stock Market Segmentation Analysis

## Overview
MarketMingle provides an analytical view into the realm of stock market investments, aiming at enhancing portfolio diversification for maximizing earnings. In the volatile landscape of the stock market, maintaining a diversified portfolio is pivotal for yielding higher returns and minimizing risks. This project employs cluster analysis to categorize stocks based on their financial indicators and performance metrics, facilitating investors in making informed decisions to safeguard against market downturns.

## Project Objectives
- To perform cluster analysis on stocks listed under the New York Stock Exchange using various financial indicators.
- To identify stocks that exhibit similar characteristics and those with minimal correlation, aiding in portfolio diversification.
- To provide insights on the clustering to help investors analyze stocks across different market segments effectively.

## Data Insights
The dataset includes information on stock prices and financial indicators for several companies, comprising 340 observations across 15 variables. The dataset features no missing values but contains outliers that were addressed during preprocessing. The variables include a mix of categorical and numerical data types, with no duplicates present.

## Exploratory Data Analysis (EDA) Highlights
- Analysis revealed industrials and financial sectors as prominent within the dataset.
- Stock prices are skewed to the right, indicating a concentration of stocks at lower price ranges with outliers on the higher end.
- The percentage change in stock prices over 13 weeks and the standard deviation of stock prices exhibit distinct distributions, providing insights into market volatility and performance.

## Cluster Analysis
### K-means Clustering:
- The elbow curve method indicated an optimal cluster count of 6, while silhouette scores suggested 3 as a viable alternative.
- Three distinct clusters were identified, each representing stocks with specific characteristics in terms of stock price, P/E ratio, and ROE, among others.

### Hierarchical Clustering:
- Hierarchical clustering corroborated the findings from K-means, with 'ward' linkage showing clear differentiation between clusters.
- The analysis further refined the stock categorizations, providing a nuanced view of market segmentation.

## Business Insights and Recommendations
- Cluster analysis revealed distinct groups of stocks with varying levels of performance, risk, and financial health.
- Specifically, Cluster 2 from both K-means and Hierarchical clustering showed promising investment opportunities with favorable financial ratios.
- Conversely, certain clusters indicated lower financial performance, suggesting a cautious approach for investors.

## Conclusion
MarketMingle leverages cluster analysis to demystify stock market investments, offering a structured approach to portfolio diversification. By identifying stocks with similar financial behaviors and minimal correlation, investors can navigate market complexities more effectively, optimizing their investment strategies for better risk management and return on investment.

*Note: This project is part of the coursework from University of Austin's post graduate program.*
