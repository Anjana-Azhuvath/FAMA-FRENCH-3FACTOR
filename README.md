# FAMA_FRENCH_3FACTOR

This project analyzes stock returns using the Fama-French factor model and compares it to the Capital Asset Pricing Model (CAPM).
## Overview
The analysis focuses on the following stocks over a 3-year period (April 2021 - April 2024):

- Apple (AAPL)
- AbbVie (ABBV)
- Delta Air Lines (DAL)
- Google (GOOGL)
- General Motors (GM)
- JPMorgan Chase (JPM)
- Verizon (VZ)

## Key Components

- Data loading and preprocessing
- Fitting the Fama-French 3-factor model
- Fitting the CAPM model
- Comparing residual correlations between models
- Log-likelihood ratio test to compare model suitability

## Key Findings

- The Fama-French model tends to have smaller cross-correlations compared to CAPM, suggesting an improvement over CAPM.
- Log-likelihood ratio test indicates that including additional factors (SMB and HML) in the Fama-French model provides statistically significant improvements over CAPM.
