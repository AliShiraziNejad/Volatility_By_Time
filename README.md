
# 30 Minute Volatility Presentation

## Overview
This analysis delves into the volatility patterns within 30-minute intervals, focusing on the past 30 trading days. The primary objective is to identify peak volatility hours, which can be pivotal for futures traders and others aiming to capture the trend during these times. Specifically, this analysis can be useful for ES derivatives traders and SPY/SPX options traders.

## Contents

- **Version Control**: A section to keep track of the notebook's versions.
- **Calculating n trading days ago**: How to compute the date for 'n' trading days in the past.
- **Pulling data from Polygon.io API**: Leveraging the Polygon.io API, which offers up to two years of free historical data.
- **Getting cash session data only**: Focusing on the cash session of SPY.
- **Pre-Bootstrap**: Introduction to the data's distribution and the challenges associated with it.
- **Bootstrap Time**: Implementation of the bootstrap sampling technique to simulate different samples and make the data more interpretable.
  - **Q-Q Plot Test for Normality**: A graphical tool to verify if the dataset follows a normal distribution.
  - **Histograms and Box Plots of the bootstrapped data**: Visual representations to better understand the data distribution.
  - **Rankings of the 30-minute intervals**: Understanding the volatility rankings within the 30-minute intervals.
- **Decay of scores**: Visualization to understand the rapid decay of volatility as intervals are ranked lower.
- **Last Updated**: Date of the last update to the notebook.

## Key Insights

1. The choice of studying the past 30 trading days offers insights into recent changes in volatility.
2. Bootstrapping, a robust technique, is used to simulate different samples making little assumptions about the data's distribution.
3. The Q-Q plot is a tool used to verify the normality of a dataset.
4. The scores are ranked based on volatility, with intervals having a higher coefficient of variation being penalized.

## Last Updated
June 28, 2023
