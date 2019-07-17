# Hate Crimes in the United States
This is Yaoli Ma's Capstone Project on Hate Crimes in the United States for [Data and Policy Summer Scholar (DPSS) Program](https://www.summerscholar.uchicago.edu/) 2019 at Harris School of Public Policy, University of Chicago. This project would not have been possible without the supervision of [Daniel Snow](https://www.dfsnow.me/about/).

In this Capstone Project, I examine the potential causes/correlates of hate crimes in the United States. The goal is to replicate [this analysis](https://fivethirtyeight.com/features/higher-rates-of-hate-crimes-are-tied-to-income-inequality/) from FiveThirtyEight using updated hate crime data and additional regressors. Background information on hate crimes and hate crime data collection in the United States can be found in [this Southern Poverty Law Center brief](https://www.splcenter.org/20180415/hate-crimes-explained#collection).

## Data
The data for this project comes from several sources:
1. FBI's [Hate Crime Statistics Program](https://www.fbi.gov/services/cjis/ucr/hate-crime)
   - Average annual hate crimes per 100,000 residents (2008 - 2017)
2. Census Bureau’s [American Community Survey](https://www.census.gov/programs-surveys/acs)
   - Median household income (2012 - 2016)
   - Percentage of population unemployed (2012 - 2016)
   - Percentage of population with only high school degree (2012 - 2016)
   - Percentage of white population below poverty line (2012 - 2016)
   - GINI index (2012 - 2016)
   - Percentage of non-white population (2012 - 2016)
3. [Kaiser Family Foundation](https://www.kff.org/a4327ef/)
   - Percentage of non-citizen population (2012 - 2016)
4. Gallup's [U.S. Daily Tracking Survey](https://www.gallup.com/analytics/213617/gallup-analytics.aspx)
   - Percentage of LGBT population (2012 - 2016)
   - Percentage of Muslim population (2012 - 2016)

## Tasks
This project accomplishes the following tasks:
1. Collect state-level data for the variables mentioned above and combine all of the variables into a single data frame.
2. Using state-level geographic data from the Census Bureau, create a map of hate crimes per 100,000 residents in 2017. 
3. Create a plot that displays the change in hate crimes per 100,000 residents during 2008 - 2017.
4. Create three multivariate linear regression models to assess whether the socioeconomic indicators exert significant influences on the hate crime rates across the country.
5. Create one additional plot using state-level hate crime and LGBT population data during 2012 - 2016.
