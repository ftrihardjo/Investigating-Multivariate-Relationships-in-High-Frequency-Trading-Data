# Investigating Multivariate Interdependencies in High-Frequency Trading Data

## Data Collection
This dataset comprises high-frequency trading information for Chinese futures, sourced from https://www.kaggle.com/datasets/wentinglu/highfrequency-futures-data-china. Records are taken at minute intervals and feature seven key columns:
1. Time (recorded in minute increments)
2. Opening Price
3. Highest Price
4. Lowest Price
5. Closing Price
6. Trading Volume (quantified in trading units)
7. Trading Amount (expressed in yuan)
8. Open Interest (the cumulative number of futures or option contracts that have been initiated but not yet finalized through transactions, deliveries, exercises, etc.)

## Data Analysis and Visualization
The heatmap of the correlation matrix indicates a significant positive correlation between the opening, highest, lowest, and closing prices. A similar strong positive correlation is observed between trading volume and trading amount. Over the timeline, prices showed a downward trend, especially during the trade war's early stages in 2018, which was followed by a notable decline at the start of the COVID-19 pandemic, and a subsequent phase of rapid recovery. The cumulative trading volume appears to increase linearly, suggesting a relatively consistent trading volume throughout the observed period. Open interest peaked in 2015 and has generally shown an upward trend until the onset of the COVID-19 pandemic.

## Anomaly Detection and Analysis
Extreme trading amounts and open interest lead to anomalies. Approximately 19.44% of the dataset consists of these anomalies.

## High-Level Summary and Conclusions
The analysis reveals a strong positive correlation among the opening, highest, lowest, and closing prices, as well as between trading volume and trading amount. Over time, prices declined, particularly during the initial stages of the 2018 trade war and at the beginning of the COVID-19 pandemic, followed by a rapid recovery. Cumulative trading volume showed a steady increase throughout the observed period, while open interest spiked in 2015 and rose until the pandemic's onset. Additionally, anomalies were identified, primarily driven by extreme values in trading amount and open interest, with about 19.44% of the dataset classified as anomalies.