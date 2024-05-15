### "Housing Prices and Homelessness: A Comprehensive Analysis"

## Overview
"How do housing prices and rental prices correlate with homelessness trends over time?"

  - By conducting thorough analyses of ousing prices and rental prices, you can gain valuable insights into the housing market dynamics and their potential impact on homelessness. These insights can help inform strategies for addressing homelessness and improving housing stability in affected communities.

  - [Slide Deck](https://docs.google.com/presentation/d/1rWzFMZlgYeZn-mr1Kjt6djbUY5lJ5azxxvPJuQRfdh4/edit?usp=sharing)

## Data Sources
- [Zillow](https://www.zillow.com/research/data/)
- [PIP Homelessness Data](https://www.huduser.gov/portal/sites/default/files/xls/2007-2023-PIT-Counts-by-State.xlsb)
- **Transaction Data:** Deed and mortgage transaction data, including information on property sales, sale prices, mortgage amounts, and foreclosure activity.
- **Neighborhood Attributes:** Neighborhood data such as crime rates, school quality, proximity to amenities, and transportation access.

## Team Members and Tasks

### Team Member 1 - Victoria
#### Tasks:
 - **Data Collection:** Gathered Zillow data on bottom tier home sales, top tier home sales, and rental prices from 2015 to 2023.
- **Analysis of Home Sales:** Analyzed trends in bottom tier and top tier home sales over time.
  - Examined changes in median home prices for bottom tier and top tier homes from 2015 to 2023.
  - Identified states with significant fluctuations in home prices and sales activity.
- **Analysis of Rental Prices:** Investigated trends in rental prices over the same period.
  - Explored changes in median rental prices from 2015 to 2023.
  - Identified states where rental prices experienced notable increases or decreases.
- **Correlation Analysis:** Conducted a correlation analysis between home prices and rental prices.
  - Calculated the correlation coefficient between home prices and rental prices to assess their relationship.
  - Explored how changes in home prices might correlate with changes in rental prices.
- **Visualizations:** Created visualizations to illustrate trends in home sales and rental prices.
  - Developed line plots to visualize trends in home sales and rental prices over time.
  - Created scatter plot to depict the correlation between home prices and rental prices.


### Team Member 2 - Syed
#### Tasks:
- **Data Collection:**
  - Access homelessness count data for each state from 2007 to 2023.
  - Compile and organize the data to ensure consistency and completeness.
- **Analysis:**
  - Conduct statistical analysis to identify trends, fluctuations, and patterns in homelessness counts over time.
  - Explore variations in homelessness rates across different states and years to understand regional differences and temporal trends.
- **Visualizations:**
  - Create line plots to visualize the trend of homelessness counts over the years for each state.
  - Generate bar charts to compare homelessness counts between states or to show changes over time.
  - Use appropriate labels, titles, and colors to enhance the clarity and effectiveness of the visualizations.

### Team Member 3 - Derick
#### Tasks:
- **Data Collection:**
  - Retrieve demographic data of homeless individuals for each state from 2007 to 2023.
  - Ensure the data includes information such as age, gender, race/ethnicity, and any other relevant demographic variables.
- **Analysis:**
  - Analyze the demographic profiles of the homeless population to identify trends and variations over time and across states.
  - Explore changes in the composition of the homeless population in terms of age groups, gender distribution, racial/ethnic diversity, etc.
- **Visualizations:**
  - Create bar charts or pie charts to visually represent the demographic distributions of homeless individuals.
  - Utilize appropriate visualization techniques to effectively communicate insights regarding demographic variations.

### Team Member 4 - Elisabeth
#### Tasks:
- **Data Collection:**
  - Collect data on the distribution of homelessness counts by housing type and sheltered status for each state from 2007 to 2023.
  - Ensure the data includes information on the number of sheltered and unsheltered homeless individuals, categorized by housing type.
- **Analysis:**
  - Analyze variations in the proportion of sheltered and unsheltered homeless individuals across states and over time.
  - Investigate any trends or changes in the distribution of homelessness by housing type and sheltered status.
- **Visualizations:**
  - Create stacked bar charts or pie charts to visually represent the distribution of homeless individuals by housing type and sheltered status.
  - Use appropriate visualization techniques to effectively convey insights into the distribution patterns of homelessness.

## Data Integration
1. **Combine Transaction Data and Neighborhood Attributes:**
   - Merge transaction data (e.g., property sales, sale prices, mortgage amounts, foreclosure activity) with neighborhood attributes data (e.g., crime rates, school quality, proximity to amenities, transportation access) by state and year.
   - Ensure consistency in data formatting and alignment to facilitate integration.
2. **Integrate Homelessness Data:**
   - Align homelessness count data with demographic characteristics and housing type/sheltered status data by state and year.
   - Verify data accuracy and completeness before integration.
3. **Align Datasets:**
   - Ensure proper alignment of all datasets by state and year.
   - Standardize state and year identifiers across datasets to ensure consistency and accuracy.
   - Verify data integrity and resolve any discrepancies or inconsistencies.
4. **Perform Data Validation:**
   - Validate integrated datasets to ensure accuracy and completeness.
   - Address any data quality issues or anomalies identified during the validation process.
5. **Document Data Integration:**
   - Document the steps taken to integrate the datasets, including any data transformations or preprocessing steps applied.
   - Maintain clear documentation to facilitate reproducibility and transparency in the analysis.

## Visualizations
1. **Create Scatter Plots:**
   - Visualize the relationship between property sales activity and homelessness counts.
   - Plot neighborhood attributes against homelessness trends to identify patterns.
2. **Generate Heatmaps:**
   - Use color gradients to represent the strength and direction of correlations between variables.
   - Create heatmaps to highlight areas with strong correlations between demographic profiles, housing market dynamics, and homelessness trends.
3. **Develop Choropleth Maps:**
   - Map homelessness rates, demographic characteristics, and housing market indicators across different geographic regions.
   - Use choropleth maps to visualize regional variations and identify areas with higher homelessness rates or specific demographic profiles.
   - Load geospatial data using geopandas.
   - Ensure alignment between geospatial data and attribute data.
   - Plot choropleth maps using matplotlib and geopandas.

## Interpretation and Insights
1. **Interpret Correlation Findings:**
   - Analyze the implications of correlation coefficients for understanding homelessness trends and underlying factors.
   - Interpret the strength and direction of correlations to identify significant relationships.
2. **Derive Insights for Policy-Making and Urban Planning:**
   - Consider the implications of correlation analysis for informing policy interventions aimed at addressing homelessness.
   - Evaluate the potential impact of housing market dynamics, neighborhood attributes, and demographic factors on homelessness rates.
3. **Provide Recommendations for Social Interventions:**
   - Suggest strategies for improving housing stability and addressing homelessness based on correlation analysis findings.
   - Offer recommendations for targeted social interventions to support vulnerable populations and mitigate homelessness risks.

## Conclusion
Summarize the key findings and potential next steps.
