# Capstone-I

## Outline

- Data Source

- Data Pre-processing

- EDA for Covid-19 Cases/Death, House for Sale, Sold House, and House for Rent

- Statistical Analysis

## Steps

1. Get the data by using Realtor API(check the Code folder)

2. Extract the data for the Philadelphia PA

3. Pre-processing the data to get rid of useless features, convert JSON format to DataFrame, and also split some single columns which has more information into multiple columns(check the Code folder)

4. EDA(check the EDA folder)

- Covid-19
    - Cases and hospitalizations-age
    - Cases and hospitalizations-sex
    - Cases and hospitalizations-race
    - Deaths-age&sex
    - Deaths-race

- House for Sale
    - Amount of different property types
    - Median Listing Price by Property Type
    - Median Listing Price by Postal Code
    - Unit building price by postal code
    - Unit lot price by postal code
    - Unit price by postal code
    - Positive cases and unit price by postal code
    - Negative cases and unit price by postal code
    - All cases and unit price by postal code
    - Hospitalizations per median listing price
    - Rate of mortality per median listing price

- Sold House
    - Total of properties sold
    - Days on the market
    - Median active sales price

- House for Rent
    - T-test for mean rent price on Februray and October
    - Rent house distribution in different region
    - Number of beds distribution
    - Density heatmap for the neighborhood and price
    
5. Statistical Analysis(Check EDA Folder)
- Means of the current and historical real estate data?
- Is there a difference in the top & bottom 10 postal codes effected by COVID-19?
- Differences stay consistent when focusing on the mean price per square foot?
