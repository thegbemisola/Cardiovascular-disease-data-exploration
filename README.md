# Cardiovascular disease data exploration
Cardiovascular diseases(CVDs) are group of disorders of the heart and blood vessels. They include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. According to WHO, _CVDs are the leading cause of death globally, taking an estimated 17.9 million lives each year._

This analysis explores risk factors for cardiovascular diseases. The dataset was gotten from [kaggle](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) and consists of 70 000 records of patients data. _(All of the dataset values were collected at the moment of medical examination.)_ 
## Methodology
* Data Wrangling
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
## Dataset Overview
The dataset consisted of 70,000 rows patients records, and 13 variables including age, weight, height, systolic bp ,diastolic bp and many others. I performed cleaning on the data while also discovering outliers and incorrect values in the dataset.
## Summary of findings
**Univariate Analysis:**
* The data had an approximately 50/50 share of those that had cvd and those that didn't.
* Data includes 30.26% more females than males.
* The data captures adults. Age ranged majorly 39-64years with 4 values aged 29&30.
* The 25 percentile of systolic and diastolic blood pressures were 120 & 80 respectively. That is, 75% of the data had elevated or high blood pressures.
* Common intervals for height was 164-165cm while weight was 68-72kg.
* Other variables (cholesterol, glucose, alcohol etc) had more positive instances than negative; Majority of the data had normal cholesterol and glucose levels, are not smokers, not drinkers and are active.

**Bivariate Analysis:**
* Each age had a share of cvd present but it's increased among older aged groups.
* About 75% of the data that had systolic and diastolic bp greater than or equal to 120 & 80 had cvd.
* The categorical fetaures had little effect on the distribution of data

**Multivariate Analysis:**
* Age and blood pressures had more effect on cvd irrespective of the cholesterol, glucose level not smoking etc.

## Key Insights for Presentation
* For the presentation, i focused on ages as an effect of cardiovascular diseases.The older people get their chances of having cardiovascular disease increase.
* Also, high blood pressures are primary risk factors of cardiovascular diseases. An increase in systolic or diastolic not neccessarily both can lead to cardiovascular diseases.
* Lastly, cvd happens overtime and different factors contribute to it.
