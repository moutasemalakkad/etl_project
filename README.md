### ETL Project (Extract, Transform, Load)

## Background:

__In this project our goal is to form a database that contains data that can help answer the following questions:__
- Cause of death by Zipcode
- The main underlying cause of death at any given Zipcode
- Analyze the correlation between income and number of deaths
- Analyze the correlation between unemployment precentage and the number of deaths

# Extracting the Data:
1 We have downloaded a csv that contains close to 28000 rows of Data from the IRS website that contains a lot of infomration that can help such analysis such as:
  - Zip Codes
  - Number of tax returns (help measure unemployment)
  - Average total income
  - Gross Income
 
 2 Downloaded a csv from Kaggle that contains close to 65000 rows this data set contains:
   - The number of cause of death per zipcode per year (not aggregated)
   
   - Longtitudes and Latitudes that can be helpful if we decide to build visualizations such as HeatMaps
   
 3 Data-set from Kaggle that contains population per zipcode
   - That is crucial for all the analysis
