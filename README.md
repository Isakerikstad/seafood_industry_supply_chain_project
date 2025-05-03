# Norwegian Seafood Supply Chain Analysis

## Overview
This repository contains data analysis and visualization projects focusing on the Norwegian seafood industry's supply chain, export patterns, and fishing activities. The analyses examine trends in seafood production, export markets, and fishing vessel activities using multiple datasets spanning from 2000 to 2025.

## Project Contents

### Analysis Notebooks
- **seafood_supply_chain_analysis.ipynb**: Core analysis of the Norwegian seafood supply chain
- **export_commodity_analysis.ipynb**: Analysis of Norwegian seafood export commodities
- **fishing_activity_seasonality.ipynb**: Analysis of seasonal patterns in fishing activities

### Data Sources
- **UN_trade_fish_2000_2023**: UN trade data for fish exports and imports (2000-2023) https://data.un.org/Data.aspx?d=ComTrade&f=_l1Code%3A4
- **UN_trade_fish_2009_2010_2011**: Focused UN trade data for specific years https://data.un.org/Data.aspx?d=ComTrade&f=_l1Code%3A4
- **SSB_salmon_weekly_2009_2011**: Weekly salmon data from Statistics Norway
- **fishing_vessel_AIS_2021_2024**: Automatic Identification System (AIS) data for fishing vessels (2021-2024). Taken from https://globalfishingwatch.org/data-download/datasets/public-fishing-effort. This was way to big a file to store here.
- **sjømatråd_eksport_månedlig**: Monthly export data from the Norwegian Seafood Council

## Key Insights
The analyses in this repository explore several critical aspects of Norway's seafood industry:

1. **Export Patterns**: Norway's position as a leading seafood exporter, with Atlantic salmon being the dominant export product
2. **Market Diversification**: Examination of export destinations and market trends
3. **Seasonal Fishing Activity**: Analysis of fishing vessel movements and seasonal patterns
4. **Supply Chain Dynamics**: Mapping the flow of seafood products from harvest to international markets
5. **Using ML**: Sort of ridiculous experiment using so few data points, but the premise of ML experiement was at least inspired from https://fisheries-2023.sites.olt.ubc.ca/files/2024/09/2024-01-Working-Paper-Price-Prediction.pdf "Advanced Machine Learning for Fish Price", and seeing if XGBoost also proved best on the data we had.

## Acknowledgements
Data sources include the United Nations Comtrade Database, Statistics Norway (SSB), the Norwegian Seafood Council, and AIS vessel tracking systems.
