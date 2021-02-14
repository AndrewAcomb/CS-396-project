COVID data by county
https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv

House prices by county
Top-tier: https://files.zillowstatic.com/research/public_v2/zhvi/County_zhvi_uc_sfrcondo_tier_0.67_1.0_sm_sa_mon.csv
Bottom-tier: https://files.zillowstatic.com/research/public_v2/zhvi/County_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_mon.csv

Library for mapping to counties
https://plotly.com/python/county-choropleth/

A mistake we're actively trying to avoid making
https://xkcd.com/1138/

Cleaned Dataset Info:

Observations: 2845 (number of counties we have data for)
Features: 54 (listed below)

—Primary Key—
FIPS (Federal Information Processing Standard number, e.g, 60037)

—County Info—

County (Name of county, e.g, ‘Los Angeles’)
Metro (Metro area of county, e.g, ‘Los Angeles-Long Beach-Anaheim’)
SizeRank (Size rank of county, e.g, 1)
State (State abbreviation of county, e.g, ‘CA’)
StateName (State name of county, e.g, ‘California’)

—COVID cases from January 2020 (\_01) to December 2020 (\_12)—

01_cases
02_cases
…
12_cases

—COVID deaths from January 2020 (\_01) to December 2020 (\_12)—

01_deaths
02_deaths
…
12_deaths

—Top tier Zillow Home Value Index (ZHVI) from January 2020 (\_01) to December 2020 (\_12)—

01_ZHVI_Top
02_ZHVI_Top
…
12_ZHVI_Top

—Bottom tier Zillow Home Value Index (ZHVI) from January 2020 (\_01) to December 2020 (\_12)—

01_ZHVI_Bot
02_ZHVI_Bot
…
12_ZHVI_Bot
