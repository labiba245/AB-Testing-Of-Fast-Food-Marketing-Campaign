# AB-Testing-Of-Fast-Food-Marketing-Campaign

This project is a A/B testing of three types of promotions by a fast food chain.

## Project Objective

Analyse A/B testing results to determine which promotional strategy works the best.

## Code and Resources Used

Python version: 3.8
Packages used: pandas, matplotlib, seaborn, scipy
Data source: https://www.kaggle.com/chebotinaa/fast-food-marketing-campaign-ab-test

## Project Description

### From explanatory analysis
Promotion 3 generated the most sales followed by 1 and 2.
Most of the promotions were done in the medium sized stores, followed by large and small-sized stores.
Majority of the stores are less than 10 years old.

### From A/B testing

#### Null hypothesis:
There is no statistically significant difference between the two types of promotions. 

I printed the t and p values comparing each type of promotion to check which ones reject the null hypothesis and which ones don't. 

Note:
The greater the magnitude of t-value, the greater the evidence against the null hypothesis.
The lower the p-value, the greater the statistical significance of the observed difference. Null hypothesis can be rejected if the p-value is less than 0.05. 

## Analysis
Promotion 1 and Promotion 3 both outperform promotion 2 but the difference between promotion 1 and 3 is not statistically different. Therefore, the company can use either promotion 1 or 3. 




