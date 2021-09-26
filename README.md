# Sales-prediction-for-BigMart
Sales prediction for different items at multiple BigMart Outlets

There were some repititions in some features, they were replaced and reduced to appropriate variables.
There were also missing values in a column, which on closer obervation,can be filled exactly instead of mean, etc, by creating a dictionary contaning the values for the same feature for a different entry, and then mapping the entire dictionary.
One of the feature, contained more than 25% of missing values, and didn't seem to be possible to fill exactly, so it was dropped.
Label Encoding was done on the categorical features.
Some basic models and ensemble models were used, and attempts were made to improve predictions by feature selection
Since this is a regression task, chi squared and annova wont work.
RFE was also tried and yeilded the maximum performance. 
