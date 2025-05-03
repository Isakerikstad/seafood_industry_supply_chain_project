I'll create the text for a README file for your seafood supply chain project. This will provide an overview of your project, its purpose, data sources, and how to navigate the repository.

# Norwegian Seafood Supply Chain Analysis

## Overview
This repository contains data analysis and visualization projects focusing on the Norwegian seafood industry's supply chain, export patterns, and fishing activities. The analyses examine trends in seafood production, export markets, and fishing vessel activities using multiple datasets spanning from 2000 to 2025.

## Project Contents

### Analysis Notebooks
- **seafood_supply_chain_analysis.ipynb**: Core analysis of the Norwegian seafood supply chain
- **export_commodity_analysis.ipynb**: Analysis of Norwegian seafood export commodities
- **fishing_activity_seasonality.ipynb**: Analysis of seasonal patterns in fishing activities

### Data Sources
- **UN_trade_fish_2000_2023**: UN trade data for fish exports and imports (2000-2023)
- **UN_trade_fish_2009_2010_2011**: Focused UN trade data for specific years
- **SSB_salmon_weekly_2009_2011**: Weekly salmon data from Statistics Norway
- **fishing_vessel_AIS_2021_2024**: Automatic Identification System (AIS) data for fishing vessels (2021-2024). Taken from https://globalfishingwatch.org/data-download/datasets/public-fishing-effort. This was way to big a file to store here.
- **sjømatråd_eksport_månedlig**: Monthly export data from the Norwegian Seafood Council

### Visualizations
- **norwegian_seafood_exports_2007_2013.png**: Visualization of Norwegian seafood exports (2007-2013)
- **fishing_Activity_seasonality.png**: Visualization of seasonal patterns in fishing activities

## Key Insights
The analyses in this repository explore several critical aspects of Norway's seafood industry:

1. **Export Patterns**: Norway's position as a leading seafood exporter, with Atlantic salmon being the dominant export product
2. **Market Diversification**: Examination of export destinations and market trends
3. **Seasonal Fishing Activity**: Analysis of fishing vessel movements and seasonal patterns
4. **Supply Chain Dynamics**: Mapping the flow of seafood products from harvest to international markets

## Data Format
The datasets contain various formats including:
- Trade values (USD)
- Export/import weights (kg)
- Vessel movement data
- Time series of commodity prices

## Using This Repository
Each Jupyter notebook contains detailed analysis with code, visualizations, and interpretations. The notebooks can be run independently to explore different aspects of the seafood supply chain.

## Future Work
- Integration of climate data to analyze environmental impacts on fishing activity
- Price prediction models for major seafood commodities
- Network analysis of international trade relationships
- Sustainability assessment of fishing practices

## Acknowledgements
Data sources include the United Nations Comtrade Database, Statistics Norway (SSB), the Norwegian Seafood Council, and AIS vessel tracking systems.
