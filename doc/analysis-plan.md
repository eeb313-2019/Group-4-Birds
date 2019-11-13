# Possible analyses

Possible data manipulations before analyses:

- For the climate data, we select the daily *mean temperature* and *mean precipitation* columns from each climate
 report from 1991 to 2015, and combine them into a single dataset by matching columns.
- For the abundance data, we select *daily counts* of Western Sandpiper during the migration period from 1991 to 
  2015 and remove NAs.
- We merge the climate and abundance datasets into one mega-dataset by *dates* in a 24-year time interval. 

Possible statistical analysis:

- To investigate whether the population abundance changes over the years, we calculate the mean daily counts of
Western Sandpiper during the migration period for 24 years. We then do a regression test between years and mean daily counts.
- To investigate whether temperature and precipitation differ through the years, we use two one-way ANOVA tests.  
- A correlation test between daily temperature and precipitation.
- A multiple linear regression test: daily Western Sandpiper observation counts ~ daily local temperature * daily local precipitation. Perform model selection.


# Possible results tables

- Regression output
- Summary of ANOVA test results
- A table of all the regression models and their AIC/AIC~c~ scores

# Possible results figures

- A plot of the population abundance over 24 years: mean daily counts vs. year.
- A plot of population trend each year: daily counts vs date.
- A plot of the temperature and precipitation over 24 years: mean temperature and precipitation during the migration period vs. year.
- A plot of the peak dates vs. years.
