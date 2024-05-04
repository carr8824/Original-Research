# Does Psychological Dynamics Affect Managerial Decisions?

This folder houses my research exploring the psychological dynamics influencing managerial decision-making in mutual funds facing scale flow challenges. This study specifically examines how managers react to substantial inflows and outflows, which may compel them to expand or contract their portfolios aggressively.

### Research Overview

We employ a testing identification strategy by contradiction to challenge the well-established theory by Berk and Green (2004), which primarily considers economic factors. Our research suggests that this theory overlooks crucial psychological elements, such as managers' perceptions of threats and rewards, and how these perceptions influence decision-making, particularly when incorporating investment opportunities with favorable net present values.

### Identification Strategy

#### Trading Selectivity (Purchases and Sales)

**Concept:** Trading Selectivity measures the ability of managers to anticipate price movements, providing a metric independent of past choices and market dynamics. This measure draws on the methodology used in the paper "Impatient Trading, Liquidity Provision, and Stock Selection by Mutual Funds" by Da, Gao, and Jagannathan (2011).
- [Read the Da, Gao, and Jagannathan paper](https://academic.oup.com/rfs/article/24/3/675/1589898)

#### Concept and Focus

- **Managerial Decision Assessment:** Unlike broader measures like Characteristic Selectivity (CS), detailed by Daniel et al. (1997), Trading Selectivity evaluates immediate, realized trades at the end of each quarter. This focus offers insights into the value managers add through decisions made within that specific timeframe.
  - [Learn about Characteristic Selectivity (CS)](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1540-6261.1997.tb02724.x)
  - For details on how to calculate the CS measure, refer to the 'CS_DGTW.R' code in my [Performance Measures repository](https://github.com/carr8824/Paper-Replications/tree/main/Asset%20Management%20and%20Pricing/Performance%20Measures).

- **Relative Measure:** Trading Selectivity is a relative measure that evaluates the effectiveness of managers' purchase decisions compared to a benchmark with similar characteristics. It focuses on the potential value added by these decisions rather than on realized performance metrics like alpha or NAV-based returns.

### Current Research Status

The ongoing research focuses on empirically identifying factors under-considered by the current literature and traditional flow and portfolio size theories. We perform a coherent testing procedure where, instead of testing directly a hypothesis, we test various alternative hypotheses. By rejecting these alternatives, we lend credence to a psychological hypothesis despite it not being directly observable. This method involves "proof by contradiction" or, in a statistical context, using "null hypothesis significance testing" (NHST).

### Feedback and Collaboration

I am open to feedback and would greatly appreciate any insights or suggestions that can help improve this work. Please feel free to engage and discuss any aspect of this research. You can contact me at revilla@uji.es or carr8824@gmail.com.



