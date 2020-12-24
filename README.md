## Hypothesis-Testing

Objective: Making predictions on whether elected MPs from certain zone or state will fullfill his/her duties or not?

Data Collection: I received the structured dataset from a website.

Data Exploration: There was one column where all MPs are labeled with '1' and '0', 1- %attendance is above 50 and 0-below 50. I counted the MPs first with those labeled. and groupby them with zones. Now I have number of MPs from each zones. 

Statistical test: Performed chi-square test here to proove the given statement in the form of rejecting the Null hypothesis. As our variable are categorical variables, that's why I chose chi-square test here and calcualted the p-value came 0.04 which is less than 0.05(significance level), So I rejected the Null hypothesis and concluded that there are 95% certainty that MPs are not fullfilling their duties 
