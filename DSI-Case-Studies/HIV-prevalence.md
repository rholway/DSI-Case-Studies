# Forecasting-HIV-Infections Case Study

### Case Study Goal:
 - To accurately model HIV incidences (new infections per 100,000) in US counties by building a linear regression model that utilizes HIV infection data, census data, data on the opioid crisis, and data on sexual orientation.

 - Identify features that are the most significant drivers of HIV infection rates and learn how these drivers differ between different regions.

### Organization:

 - Upload data and perform EDA
 - Set target as 'prevalence'
 - Write models to see affects of different features

### Description of problem and data:

 - Problem: optimizing features

 - Target: 'HIVprevalence'
 - Features: Drug dependency, poverty, morphine milligram equivalents per capita, rate, unemployment rate, drug death rate

### Accomplished

 - Ran scatter_matrix and reviewed correlation coefficients to identify strong correlates of target

 - Built model

##### Poverty Rate Box Plot
<img src='HIV-figs/PovertyRate.png' />

##### Drug Dependency Box Plot
<img src='HIV-figs/Drug Dependency.png' />

##### HIV Prevalence Box Plot
<img src='HIV-figs/HIV Prevalence.png' />

##### Methadone Milligram per Capita Box Plot
<img src='HIV-figs/Methadone Milligram Per Capita.png' />

##### OLS Model Summary Results
<img src='HIV-figs/modelsum.jpg' />

##### Scatter Plot of Residuals
<img src='HIV-figs/StudentizedResiduals.png' />

##### QQ Plot of Residuals
<img src='HIV-figs/qqplot.png' />

### After taking the log of the target we found better results

##### OLS Model Summary Results
<img src='HIV-figs/log_results.png' />

##### Scatter Plot of Residuals
<img src='HIV-figs/scatter_log.png' />

##### QQ Plot of Residuals
<img src='HIV-figs/qqplot_log2.png' />




### Learning Lessons

 - EDA takes time
 - Try new things
