# Voter Demographics & Income Inequality Analysis

## Project Overview

This project investigates the relationship between growing income inequality and political polarization in the United States from 2000-2020. 

**Primary Hypothesis**: Growing income inequality has created deep societal resentment against institutions and elites, manifesting as increased political polarization.

## Research Questions

1. Do counties/states with higher income inequality show greater shifts toward anti-establishment candidates?
2. Has the correlation between local economic inequality and voting patterns strengthened over time?
3. Are areas with stagnant median wages more likely to experience dramatic political shifts?
4. How does voting for anti-establishment candidates correlate with measures of institutional distrust?

## Data Sources

- **Economic Data**: U.S. Census Bureau (American Community Survey)
- **Political Data**: Federal Election Commission, state election offices
- **Demographic Data**: U.S. Census Bureau
- **Geographic Data**: U.S. Census TIGER/Line Shapefiles

## Methodology

- **Time Period**: 2000-2020 (presidential election cycles)
- **Geographic Level**: County and state-level analysis
- **Statistical Methods**: Panel data regression, time series analysis, geographic correlation analysis
- **Visualization**: Interactive choropleth maps, time series plots, statistical dashboards

## Project Structure

```
voter_inequality_project/
├── data/
│   ├── raw/              # Original downloaded datasets
│   ├── processed/        # Cleaned, analysis-ready data
│   └── external/         # Shapefiles, lookup tables
├── notebooks/
│   ├── exploratory/      # Initial data exploration
│   ├── analysis/         # Statistical analysis
│   └── visualization/    # Interactive visualizations
├── outputs/
│   ├── plots/           # Static visualizations
│   ├── maps/            # Interactive maps
│   └── reports/         # Final analysis reports
├── docs/
│   ├── methodology/     # Detailed methodology docs
│   └── sources/         # Data source documentation
└── requirements.txt     # Python dependencies
```

## Key Findings

*[To be updated as analysis progresses]*

## Technical Skills Demonstrated

- **Python**: pandas, numpy, matplotlib, seaborn, plotly
- **Statistical Analysis**: scipy, statsmodels, scikit-learn
- **Geographic Analysis**: geopandas, folium
- **Data Visualization**: Interactive dashboards and maps
- **Statistical Methods**: Regression analysis, time series analysis, hypothesis testing

## Installation & Usage

1. Clone the repository:
```bash
git clone [github.com/brucegav/voter-income-inequality-analysis-2000-2020]
cd voter_inequality_project
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up Jupyter kernel:
```bash
python -m ipykernel install --user --name voter_inequality_project --display-name "Voter Inequality"
```

5. Start Jupyter:
```bash
jupyter notebook
```

## Project Timeline

- **Phase 1**: Project Setup & Literature Review (Week 1)
- **Phase 2**: Data Collection (Weeks 2-3)
- **Phase 3**: Data Cleaning & Preprocessing (Weeks 3-4)
- **Phase 4**: Exploratory Data Analysis (Week 5)
- **Phase 5**: Statistical Analysis (Weeks 6-7)
- **Phase 6**: Advanced Visualizations (Weeks 7-8)
- **Phase 7**: Analysis & Interpretation (Week 8)
- **Phase 8**: Documentation & Presentation (Week 9)

## Contact

Bruce Gavins - brucegavins@gmail.com

## License

This project is for portfolio demonstration purposes.

---

*Last Updated: 9/17/25*