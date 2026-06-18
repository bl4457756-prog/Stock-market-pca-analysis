# COMP529 Big Data Analytics: CA2 (PCA Assignment)

This project focuses on applying **data preprocessing and Principal Component Analysis (PCA)** to S&P 500 stock market data using R.

---

## Techniques Used

### Data Processing (R / tidyverse)
- Cleaned and filtered large-scale stock market data
- Constructed a consistent panel dataset across multiple tickers and dates
- Aligned time-series data to ensure comparability across assets

---

### Feature Engineering
- Computed daily simple returns from adjusted closing prices
- Transformed raw price data into return-based time-series for analysis

---

### Principal Component Analysis (PCA)
- Applied PCA using `prcomp()` in R
- Extracted latent factors driving co-movement in stock returns
- Analysed principal component loadings to understand market structure

---

### Variance Analysis
- Used explained variance ratios to evaluate PCA performance
- Applied **elbow method** to select number of components
- Used cumulative variance to identify components explaining 95% of variance

---

### Standardisation
- Applied z-score scaling to returns before PCA
- Compared results with and without standardisation
- Analysed how scaling affects variance distribution and PCA structure

---

## Tools & Libraries

- R
- tidyverse
- lubridate
- inflection
- readr

---

## Summary

This project demonstrates how PCA can be used to reduce dimensionality in financial time-series data and identify underlying market-wide factors driving stock return movements.
