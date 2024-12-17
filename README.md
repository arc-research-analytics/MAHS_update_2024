# Metro Atlanta Housing Strategy Update

This repo contains the Python notebook used in the data analysis and aggregation for the [Metro Atlanta Housing Strategy update](https://metroatlhousing.org/). The Strategy includes housing policy recommendations based on findings from the regional housing market. These recommendations are tailored to specific "submarkets", which are clusters of the region where similar economic and housing dynamics are at play. Each of the 1,248 metro Atlanta Census tracts have been assigned to one of ten submarkets.

To create the submarkets, we leveraged historic land use data from Zillow to find unique "fingerprint" proportions by Census tract in a supervised learning model to predict 2023 classifications. To this, we joined sales data from ATTOM Data Solutions and various demographic and location factors to more accurately classify each of the metro Atlanta Census tracts into one of ten submarkets.

The `HousingAnalysis.ipynb` notebook walks through the above steps in much greater detail, but in order to replicate, you will need your own source data, as the raw data for the study has not been included in this repo.
