# Arctic National Wildlife Refuge Trigger Price Analysis

Real options analysis determining optimal trigger prices for oil drilling in the Arctic National Wildlife Refuge (ANWR).

## Overview

This project replicates and extends the analysis from Conrad & Kotani (2005) "When to drill? Trigger prices for the Arctic National Wildlife Refuge" using Python implementation of real options theory.

**Author:** Vanessa Quintero  
**Institution:** Universidad de Granada - Master's in Economics  
**Course:** Dynamic Macroeconomics  
**Field:** Environmental Economics & Policy Analysis

## Methodology

- **Real Options Theory**: Applied to irreversible investment decisions under uncertainty
- **Geometric Brownian Motion**: Models stochastic oil price evolution 
- **Trigger Price Calculation**: Determines optimal drilling thresholds using dynamic programming
- **Sensitivity Analysis**: Examines robustness across different economic scenarios

## Key Results

- **Baseline trigger price**: $19.84-$21.26/barrel for amenity values of $200-300M annually
- **Volatility effect**: Higher oil price uncertainty increases trigger prices (option value)
- **Growing amenities**: Environmental value growth delays optimal drilling decisions
- **Production decline**: Concentrated early revenues reduce optimal trigger prices
- **Mean reversion**: Alternative price processes yield higher trigger prices ($25.41-$31.42/barrel)

## Economic Insights

**Model validation**: All results confirm economic intuition  
**Policy implications**: Environmental valuation significantly affects drilling decisions  
**Uncertainty premium**: Volatility creates substantial option value for waiting  
**Methodological rigor**: Successfully replicates published academic results  

## Technical Implementation

**Python Libraries:**
- `pandas` & `numpy`: Data manipulation and mathematical calculations
- `matplotlib` & `plotly`: Professional visualizations and interactive plots
- `scipy`: Advanced mathematical functions for optimization

**Analysis Structure:**
- Parameter estimation and model calibration
- Trigger price calculations across multiple scenarios  
- Comprehensive sensitivity analysis
- Economic validation and robustness testing

## Files

- `Real_options_ANWR_study.ipynb`: Complete analysis with code, results, and validation
- `README.md`: Project documentation and methodology overview

## Usage

```bash
# Clone this repository
git clone https://github.com/vssaquint/ANWR-Trigger-Price-Analysis.git

# Install required packages
pip install pandas numpy matplotlib plotly scipy jupyter

# Open and run the analysis
jupyter notebook Real_options_ANWR_study.ipynb
```

## Key Findings

**Trigger Price Results ($/barrel):**
- **Flat Case**: $19.84 - $21.26 (baseline scenario)
- **Growing Amenity**: $19.99 - $21.49 (environmental value increases)  
- **Declining Production**: $19.62 - $20.93 (concentrated early revenues)
- **Mean-Reverting Process**: $25.41 - $31.42 (alternative price model)

*Range represents amenity values from $200M to $300M annually*

## Academic Reference

Conrad, J. M., & Kotani, K. (2005). When to drill? Trigger prices for the Arctic National Wildlife Refuge. *Resource and Energy Economics*, 27(4), 273-286.

## Contact

For questions about methodology or implementation details, please open an issue in this repository.
---
*This analysis demonstrates the application of advanced economic theory to real-world policy decisions using modern data science tools.*
