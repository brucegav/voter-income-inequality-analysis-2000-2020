# Methodology

## Research Design

**Type**: Observational study using panel data
**Unit of Analysis**: U.S. counties
**Time Frame**: 2000-2020 (presidential election years)
**Sample Size**: ~3,100 counties

## Key Variables

### Dependent Variables
- Vote margin changes (Republican vs. Democratic)
- Anti-establishment voting patterns
- Ticket-splitting rates
- Primary election outsider support

### Independent Variables  
- Gini coefficient (income inequality)
- Median household income changes
- 90th/10th percentile income ratios
- Employment/unemployment rates

### Control Variables
- Demographics (age, race, education)
- Population density
- Regional indicators
- Economic sector composition

## Analytical Approach

### 1. Descriptive Analysis
- Time series trends in key variables
- Geographic distribution patterns
- Correlation matrices

### 2. Statistical Modeling
- Panel data regression: ΔVoting ~ Inequality + Controls
- Time series analysis of key relationships  
- Mediation analysis for causal mechanisms

### 3. Robustness Checks
- Alternative inequality measures
- Different time periods
- Geographic subsets
- Alternative model specifications

## Software & Tools

- **Python**: Primary analysis language
- **Libraries**: pandas, numpy, scipy, statsmodels, scikit-learn
- **Visualization**: matplotlib, seaborn, plotly, geopandas
- **Environment**: Jupyter notebooks