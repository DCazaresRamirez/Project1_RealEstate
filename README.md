### "Housing Prices and Homelessness: A Comprehensive Analysis"

## Overview
"How do housing prices and rental prices correlate with homelessness trends over time?"

  - By conducting thorough analyses of housing prices and rental prices, you can gain valuable insights into the housing market dynamics and their potential impact on homelessness. These insights can help inform strategies for addressing homelessness and improving housing stability in affected communities.

  - [Slide Deck](https://docs.google.com/presentation/d/1rWzFMZlgYeZn-mr1Kjt6djbUY5lJ5azxxvPJuQRfdh4/edit?usp=sharing)

  - ## Images

Static images generated for the home/rent vs Homelessness
  - [Home Prices 10 Years](Home_Prices_Screenshots/All_Home_Prices_10_Years.png)  
  - [Home Prices Bottom 5](Home_Prices_Screenshots/Home_Prices_Bottom_5.png)
  - [Home Prices Top 5](Home_Prices_Screenshots/Home_Prices_Top_5.png)
  - [Rental Prices](Home_Prices_Screenshots/Rental_Prices_8_Years.png)
  - [Linear Regression, Home Prices vs Rental Prices](Home_Prices_Screenshots/Home_vs_Rental_Linear_Regression.png)
  - [Linear Regression, Home Prices vs Homelessness](Home_Prices_Screenshots/Home_Prices_vs_Homeless.png)
  - [Linear Regression, Rental Prices vs Homelessness](Home_Prices_Screenshots/Rent_vs_Homeless.png)

## Data Sources
- [Zillow](https://www.zillow.com/research/data/)
- [PIP Homelessness Data](https://www.huduser.gov/portal/sites/default/files/xls/2007-2023-PIT-Counts-by-State.xlsb)


## Team Members and Tasks

### Team Member 1 - Victoria
- [Housing Costs and Homelessness Notebook](homes_sales_vs_rental_prices.ipynb)
- [Bottom Tier Home Sales Notebook](https://github.com/DCazaresRamirez/Project1_RealEstate/blob/main/Home%20prices%20data/bottom_tier_home_sales.ipynb#:~:text=/-,Home%20prices%20data,bottom_tier_home_sales.ipynb,-Latest%20commit))
#### Tasks:
 - **Data Collection:** Gathered Zillow data on bottom tier home sales, top tier home sales, and rental prices from 2015 to 2023.
- **Analysis of Home Sales:** Analyzed trends in bottom tier and top tier home sales over time.
  - Examined changes in median home prices for bottom tier and top tier homes from 2015 to 2023.
  - Identified states with significant fluctuations in home prices and sales activity.
- **Analysis of Rental Prices:** Investigated trends in rental prices over the same period.
  - Explored changes in median rental prices from 2015 to 2023.
  - Identified states where rental prices experienced notable increases or decreases.
- **Correlation Analysis:** Conducted a correlation analysis between home prices and rental prices, and homelessness data.
  - Calculated the correlation coefficient between home prices and rental prices to assess their relationship.
  - Explored how changes in home prices might correlate with changes in rental prices.
  - Explored how changes in home and rental prices might correlate with homelss population trends over time.
- **Visualizations:** Created visualizations to illustrate trends in housing costs and homelessness
  - Developed line plots to visualize trends in home sales and rental prices over time.
  - Created scatter plot to depict the correlation between home prices and rental prices, and showed the linear regression.
  - Created a scatter plot of Syed's data set in the output_data folder of homeless counts by state, and showed the linear regression.
  - Created my portion of the Google Slide presentation, assigned the tasks, and input all information into the README file, as well as putting together the final conclusion.


### Team Member 2 - Syed
#### Tasks:
- **Data Collection:**
  - Access homelessness count data for each state from 2013 to 2023.
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
  - Collect data on the distribution of homelessness counts by housing type and sheltered status for each state from 2013 to 2023.
  - Ensure the data includes information on the number of sheltered and unsheltered homeless individuals, categorized by housing type.
- **Analysis:**
  - Analyze variations in the proportion of sheltered and unsheltered homeless individuals across states and over time.
  - Investigate any trends or changes in the distribution of homelessness by housing type and sheltered status.
- **Visualizations:**
  - Create stacked bar charts or pie charts to visually represent the distribution of homeless individuals by housing type and sheltered status.
  - Use appropriate visualization techniques to effectively convey insights into the distribution patterns of homelessness.

## Data Integration

- Note that due to time constraints, we were unable to integrate how the demographics of the homeless populations affects their sheltered status.

1. **Integrate Homelessness Data:**
   - Align homelessness count data with demographic characteristics and housing type/sheltered status data by state and year.
   - Verify data accuracy and completeness before integration.
2. **Align Datasets:**
   - Ensure proper alignment of all datasets by state and year.
   - Standardize state and year identifiers across datasets to ensure consistency and accuracy.
   - Verify data integrity and resolve any discrepancies or inconsistencies.
3. **Perform Data Validation:**
   - Validate integrated datasets to ensure accuracy and completeness.
   - Address any data quality issues or anomalies identified during the validation process.
4. **Document Data Integration:**
   - Document the steps taken to integrate the datasets, including any data transformations or preprocessing steps applied.
   - Maintain clear documentation to facilitate reproducibility and transparency in the analysis.

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

## Conclusion - Victoria
## Analysis Summary: Home Prices and Homeless Population

### Correlation Analysis

#### Home Prices Change vs. Homeless Counts Change
- **Correlation Coefficient**: The correlation coefficient between home prices change and homeless population change for the specified states is 0.3015. This indicates a weak to moderate positive correlation between the two variables.
- **Linear Regression Analysis**: A linear regression plot was generated to visually represent the relationship between home prices change and homeless population change. The plot shows the trend and strength of the relationship between these variables.

#### Rental Prices Increase vs. Homeless Population Change
- **Correlation Coefficient**: The correlation coefficient between rental prices increase and homeless population change is 0.5672. This suggests a moderate positive correlation between rental prices increase and homeless population change.

### Analysis of Top 5 States with the Highest Change in Homeless Population

The top 5 states with the highest change in homeless population from 2013 to 2023 are:
1. California (CA)
2. Colorado (CO)
3. Arizona (AZ)
4. New Mexico (NM)
5. Utah (UT)

### Consideration of Climate
- The top 5 states with the highest change in homeless population are generally in warmer climates, where living outdoors might be more feasible. The exception is Colorado, which has colder winters. Analyzing the sheltered status for Colorado could provide insights into how the state manages its homeless population during colder months. I did find that Colorado has a much higher population of sheltered homeless than unsheltered homeless.


### Potential Factors Influencing Homelessness
1. **Economic Conditions**: Factors such as unemployment rates, cost of living, and availability of affordable housing play a significant role in influencing homelessness rates. This must be kept in mind, as much more analysis can be done.
2. **Housing Affordability**: Rising home prices and rental rates can exacerbate homelessness, particularly for those on the edge of financial instability.
3. **Social Services Availability**: The presence and effectiveness of social services, including shelters, mental health support, and substance abuse programs, can impact the homeless population.
4. **Climate**: Warmer climates may see higher numbers of unsheltered homeless individuals, as living outdoors is more feasible. Conversely, colder climates may drive the need for more sheltered accommodations.
5. **Sheltered Status**: The ratio of sheltered to unsheltered homeless individuals provides insights into how states are managing homelessness. States with higher sheltered populations may have more robust systems in place to support the homeless.

### Derive Insights for Policy-Making and Urban Planning

#### Implications of Correlation Analysis
- **Policy Interventions**: The moderate positive correlations suggest that both home and rental price increases can lead to higher homelessness rates. Policies aimed at controlling rent and home price inflation could help mitigate homelessness. Additionally, improving affordable housing availability should be a priority.
- **Housing Market Dynamics**: Rapid increases in home prices and rents without corresponding wage growth can exacerbate homelessness. Urban planning must consider the balance between housing supply and demand, ensuring that new developments include affordable housing options.
- **Neighborhood Attributes and Demographics**: Neighborhood gentrification and demographic shifts can displace low-income residents, increasing homelessness. Policies should aim to protect vulnerable populations from displacement through rent control and inclusive zoning laws.

### Provide Recommendations for Social Interventions

#### Strategies for Improving Housing Stability
- **Affordable Housing Development**: Increase funding and incentives for the development of affordable housing units. Partner with private developers to include affordable options in new projects.
- **Rent Control Measures**: Implement or strengthen rent control measures to stabilize rental prices and prevent sudden increases that can lead to evictions.
- **Emergency Assistance Programs**: Expand emergency rental assistance programs to help individuals and families facing temporary financial hardships remain in their homes.

#### Recommendations for Targeted Social Interventions
- **Supportive Housing Programs**: Develop supportive housing programs that provide both housing and access to services such as mental health care, substance abuse treatment, and job training.
- **Shelter Expansion**: Increase the number and capacity of homeless shelters, especially in areas with high unsheltered populations. Ensure shelters are accessible year-round and provide necessary support services.
- **Preventive Measures**: Implement preventive measures such as eviction prevention programs and mediation services to help tenants and landlords resolve conflicts before they result in homelessness.
- **Data-Driven Approaches**: Use data to identify at-risk populations and target interventions effectively. Monitor and evaluate the impact of policies and programs to ensure they are achieving desired outcomes.

### Conclusion
The analysis reveals a weak to moderate positive correlation between changes in home prices and homeless population change, and a moderate positive correlation between rental prices increase and homeless population change. The top states with the highest change in homeless population are predominantly in warmer climates, particularly California,  with sheltered status playing a critical role in colder regions like Colorado. Various socio-economic factors, including housing affordability, economic conditions, and availability of social services, significantly impact homelessness rates. Understanding these dynamics is crucial for developing effective strategies to address homelessness.

