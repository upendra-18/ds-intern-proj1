# Trader Behavior and Sentiment Analysis

This project analyzes how the Fear and Greed index affects trading patterns, risk, and profit. It uses a mix of data analysis and machine learning to group traders by their behavior.

## Project Goals
* Connect market sentiment (Fear/Greed) to trader performance metrics.
* Use AI clustering to group traders into three types: Whales, Gamblers, and Pros.
* Provide rules for trading based on sentiment data.

## Setup

### Packages you need
To run this, you just need these four packages:
* pandas
* matplotlib
* seaborn
* scikit-learn

## How to Run
1. Open the analysis.ipynb file in Google Colab or Jupyter Notebook.
2. Simply run the cells in order from top to bottom.

## Main Insights
* Retail Volume: When the market hits "Extreme Greed," the number of trades doubles, but the average size of those trades drops significantly.

* Contrarian Trading: Large-scale traders tend to buy during "Extreme Fear" when most others are selling.

* Trader Types: The model successfully separates high-frequency traders (Gamblers) from high-capital traders (Whales).

