# Metro Atlanta Housing Strategy Update

This repo contains the Python notebook used in the data analysis and aggregation for the [Metro Atlanta Housing Strategy update](https://metroatlhousing.org/). The Strategy includes housing policy recommendations based on findings from the regional housing market. These recommendations are tailored to specific "submarkets", which are clusters of the region where similar economic and housing dynamics are at play.

To create the submarkets, we leveraged historic land use data from Zillow to find unique "fingerprint" proportions by Census tract in a supervised learning model to predict 2023 classifications. To this data, we joined sales data from ATTOM Data Solutions, and various factors to more accurately classify each of the metro Atlanta Census tracts into one of ten submarkets.

The `HousingAnalysis.ipynb` notebook walks through the above steps, but in order to replicate, you will need your own data sources, as the raw data has not been included in this repo.
