# Titanic lab

***

## My_EDA

### Insights_from_the_Titanic_EDA:

* Women from all classes have a survival rate better than men in any class, being those women in better classes almost guaranteed survival.
* Younger people tend to survive better.
* People who paid a lot had the highest survival rate.
* Older people were more likely to pay more, although that didn’t reflect in their survival rates.

### For_better_EDA['changes_done', 'suggestions']:
*	Cabin can be dropped, Class should give similar results
*	Ticket and Name make the study harder and don’t give any substantial pros, so they can also be dropped
*	Age and Fare can be aggregated into more manageable discrete variables using bins. Naturally, they are highly correlated with their respective aggregations, so maybe dropping them would give better results. Maybe conserving one of them and the aggregation of the other could generate also better results.
*	The variables used for the number of relatives could be aggregated into a single “relatives” variable, maybe more valuable, and maybe segmentable (mode in Class, Fare…).

***

## Looking_up_other_submissions

### Features_to_check
- any feature engineering or feature wrangling methods which you have seen? 

- did they impute any missing values? 

-  what about scaling methods for numerical variables?

- what about encoding categorical variables?

- any evidence of overfit or sampling bias ? 
