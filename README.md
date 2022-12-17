# Project Description

## Aim

To identify geographical coordinates of all hydro and wind stations in New Zealand.  

This project is a smaller part of my PhD research in electricity price forecasting. It allows me to identify key regions in New Zealand where measurements of weather variables are important. In particular, I want to access wind speed and wind direction data near wind farms, and precipication data near hydroelectric stations.

However, this project does not go beyond accessing the coordinates of power stations, since obtaining the weather data is done through a subscription-based API, and that data is not publicly available.

## Data

All relevant data is publicly available by the Electricity Authority, the governing force responsible for the regulation of the New Zealand electricity market.  
For this project, we are concerned with two particular datasets.

The first dataset is a list of all network supply points on the New Zealand electricity grid. This data holds information about all power stations in New Zealand, their generation units, and their specific location in the NZTM (New Zealand Traanscverse Mercator) coordinate system.

**Link**: <https://www.emi.ea.govt.nz/Wholesale/Datasets/MappingsAndGeospatial/NetworkSupplyPointsTable/20221217_NetworkSupplyPointsTable.csv>

The second dataset contains historical electricity generation data in New Zealand of all power stations, along with their respective fuel type.

**Link**: <https://www.emi.ea.govt.nz/Wholesale/Datasets/Generation/Generation_MD/202211_Generation_MD.csv>

This link only contains generation information November 2022, which is sufficient for this project. However, for my primary research I had to extract these monthly files dating back to January 2011, which is a longer procedure. Thankfully, the files are names in a consistent format (such as 202211_Generation_MD.csv), which made the extraction procedure relatively easy.
