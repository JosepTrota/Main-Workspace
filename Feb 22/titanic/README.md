# Titanic lab

![alt text](https://pbs.twimg.com/media/CaNgx-FWQAACiiE.png "Come on Rose...")

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

Name (click for link) | feature['engineering', 'wrangling'] | imputated: NaN [y/n] | Scaling_num | Encoding_cat | Overfit and Sampling_Bias [y/n]
---|---|---|---|---|---
[Is Jack Alive?](https://www.kaggle.com/shaz13/is-jack-alive-86-8)|a| Nulls in Age changed to reflect the correlation between age and class
All the Nulls in Cabin changed for "Not having a cabin"|a|a|Encoding Sex and Embarked in the beginning of the code|a
