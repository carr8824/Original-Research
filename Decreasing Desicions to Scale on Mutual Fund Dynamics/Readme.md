# Trading Selectivity

Trading Selectivity is a measure I have developed, drawing inspiration from the methodology in the paper "Impatient Trading, Liquidity Provision, and Stock Selection by Mutual Funds" by .[Da, Gao, and Jagannathan (2011)]((https://academic.oup.com/rfs/article/24/3/675/1589898)). 

## Concept and Focus

- **Managerial Decision Assessment**: Unlike broader measures like Characteristic Selectivity (CS) by .[Daniel et al., (1997)](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1540-6261.1997.tb02724.x), Trading Selectivity assesses immediate, realized trades at the end of each quarter. It offers insights into the value added by managers through decisions made within that specific quarter. To understand how to calculate the CS measure, refer to the 'CS_DGTW.R' code in my [Performance Measures repository](https://github.com/carr8824/Paper-Replications/tree/main/Asset%20Management%20and%20Pricing/Performance%20Measures).
- **Relative Measure**: Trading Selectivity is a relative measure, evaluating the effectiveness of managers' purchase decisions compared to a benchmark with similar characteristics. It focuses on the potential value added by these decisions, rather than on realized performance metrics like alpha or NAV-based returns.

## Decomposition Approach by Da et al. (2011)

**Trading Selectivity** adopts a focused approach from the decomposition methodology by Da et al. (2011):
- **Trading Selectivity**: Concentrates on Buy and Sell decisions.
- **Old Component**: Relates to the non-traded segment of the portfolio.
- **Adjustment Component**: Pertains to adjustments for fund inflows and outflows.

The primary emphasis of **Trading Selectivity** is on Purchase Selectivity and Sale Selectivity, providing a detailed dissection of these aspects. It specifically targets the trade-related component of CS (DGTW) and breaks down trades into distinct categories of purchases and sales selectivity.

## Data Requirements

- **Benchmark Adjusted Returns**: Essential data includes `QuarterlyCRSPBAR.dta` for benchmark-adjusted returns. This can be generated using the `BenchmarkAdjustedReturns.R` script found in my [Performance Measures repository](https://github.com/carr8824/Paper-Replications/tree/main/Asset%20Management%20and%20Pricing/Performance%20Measures).
- **Edited Fund Holdings Data (`EMFHoldings_<year>.dta`)**: This yearly dataset comprises edited mutual fund holdings sourced from CRSP or Thomson Reuters. The approach follows the Most Comprehensive, Up-to-Date Portfolio holdings methodology, as outlined in the [EditingHoldings.R script](https://github.com/carr8824/Data-Cleaning/tree/main/DoctoralResearch-AssetManagement/PortfolioHoldings%20MCU%20CRSPTHR).

