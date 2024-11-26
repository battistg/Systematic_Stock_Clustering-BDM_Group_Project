# Systematic Clustering and Prediction of S&P 500 stocks

## Executive Summary

Making the right investment choices is always a challenge for market operators, given the vast number of stocks and the ever-changing market. This project addresses the complexity of stock selection by developing a model that groups stocks based on risk and return characteristics using historical S&P 500 data.

The model simplifies the stock selection process by categorizing stocks into distinct clusters, each corresponding to a specific investor profile: conservative, balanced, and aggressive. This systematic approach improves alignment with client goals and promotes efficiency in decision-making processes. The methodology has also been successfully tested on the NASDAQ 100, demonstrating its adaptability across different markets.

---

## Features of the Project

- **Clustering with K-Means**:
  - Group stocks based on risk-return characteristics.
  - Identify stable clusters that match investor profiles.

- **Classification Trees**:
  - Use decision tree algorithms to assign stocks to clusters based on features such as volatility and mean return.

- **Scalability**:
  - The model can be extended to other indices like the NASDAQ 100.

- **Efficiency**:
  - Automates the categorization process, saving time for market operators.

---

## Data Source

The project uses historical stock prices from the **S&P 500 index**, obtained through the R package `tidyquant`.

---

## Requirements

To run the project, you need the following R packages installed:

```r
# Install packages
install.packages(c("dplyr", "tidyquant", "cluster", "caret", "rpart", "rpart.plot", "FNN"))

# Load packages
library(dplyr)
library(tidyquant)
library(cluster)
library(caret)
library(rpart)
library(rpart.plot)
library(FNN)
```

## Authors
**Giovanni Battistella**: https://github.com/battistg
**Angel Echaide**: https://github.com/angelechaide
**Gonzalo Gonzalez**: https://github.com/gonzaloignacio
**Laxmi Prabhu Kundapur**: https://github.com/Laxmi123-eng
**Lu Zhou**: https://github.com/LuZhou17
