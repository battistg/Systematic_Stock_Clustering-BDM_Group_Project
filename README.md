
## Stock Classification Model: S&P 500 Analysis


# Executive Summary

Making the right stock choices for clients is always a challenge for investment firms, given the vast number of stocks and the ever-changing market. This project addresses the complexity of stock selection by developing a model that groups stocks based on risk and return characteristics using historical S&P 500 data.

The model simplifies the stock selection process by categorizing stocks into distinct clusters, each corresponding to a specific investor profile: conservative, balanced, and aggressive. This systematic approach improves alignment with client goals and promotes efficiency in decision-making processes. The methodology has also been successfully tested on the NASDAQ 100, demonstrating its adaptability across different markets.

---

# Features of the Project

- **Clustering with K-Means**:
  - Group stocks based on risk-return characteristics.
  - Identify stable clusters that match investor profiles.

- **Classification Trees**:
  - Use decision tree algorithms to assign stocks to clusters based on features such as volatility and mean return.

- **Scalability**:
  - The model can be extended to other indices like the NASDAQ 100.

- **Efficiency**:
  - Automates the categorization process, saving time for investment firms.

---

# Data Source

The project uses historical stock prices from the **S&P 500 index**, obtained through the R package `tidyquant`. This dataset includes 500 of the largest companies traded on U.S. stock exchanges.

---

# Requirements

To run the project, you need the following R packages installed:

```{r, eval=FALSE}
install.packages(c("dplyr", "tidyquant", "cluster", "caret", "rpart", 
                   "rpart.plot", "FNN", "factoextra", "readxl", "openxlsx"))
