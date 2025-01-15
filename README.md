
### Gist Summary for GitHub Description

```markdown
Clustering cryptocurrencies using machine learning! 🚀 This project groups cryptocurrencies based on market performance using K-Means and PCA. Interactive visualizations, Elbow Curves, and clustering analysis make this a comprehensive exploration of market trends. Check out the results and contribute to the analysis! 🧠💹

# Cryptocurrency Price Change Analysis and Clustering
## Project Objectives
1. Preprocess and scale cryptocurrency market data for clustering analysis.
2. Use **K-Means clustering** to group cryptocurrencies based on price change metrics.
3. Optimise the clustering process by reducing dimensionality using **Principal Component Analysis (PCA)**.
4. Compare clustering results with and without PCA to evaluate the impact of dimensionality reduction.

## Features
- **Data Preprocessing:**
  - Cleaning and scaling raw cryptocurrency market data.
  - Handling various price change metrics over different time periods (24h, 7d, 30d, etc.).
    
- **Clustering Analysis:**
  - Group cryptocurrencies into clusters using the K-Means algorithm.
  - Use the **Elbow Method** to determine the optimal number of clusters (`k`).

- **Dimensionality Reduction:**
  - Apply PCA to reduce the number of features while preserving key variance.
  - Visualize clustering results in a simplified 2D space.

- **Visualization:**
  - Plot Elbow Curves to identify the optimal number of clusters.
  - Use interactive scatter plots (via hvPlot) to visualize clustering patterns.

### Technologies Used

- Python
- Pandas for data manipulation
- scikit-learn for machine learning algorithms
- hvPlot for interactive visualisations
- Jupyter Notebook for code development and presentation

## Credit
- This repository is for Soheil Dabooyeh's Crypto-Clustering challenge for Monash Data Analytics Bootcamp. All code written by Soheil Dabooyeh.
