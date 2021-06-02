# Analyzing Game Sales on Different platforms

### Goal of the project:
We are working on a online store as an Analyst. And we have an data about games on different platforms from 1980 till 2016(2016's not complete). And our mission is identifying which games succeds on 2017. 

Based on this data we must test hypothesis which are given below:

1. `Average user ratings of the Xbox One and PC platforms are the same.`
2. `Average user ratings for the Action and Sports genres are different.`

### Project plan:
1. Opening data files and studying general information
2. Preprocessing data
3. Analyzing data
4. Creating a user profile for each region  
5. Test the hypothesis 
6. Drawing overall conclusion

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **matplotlib.pyplot**: used as an helper library for visualize `graphs`.
3. **numpy**: used for calculating `mean`,`variance` and `standard deviation`
4. **scipy**: used for testing hypotheses
5. **warnings**: for filtering warnings.

### Conclusion drawn from the project:
We have made lots of calculations with `games` dataframe. We checked it with several filters. Firstly we determined `info` about the data. Then, we filled missing values and replaced column `datatypes`. After that,observed most profitable platforms and genres. And we observed that, in most cases there is no impact of `user_score` on `total_sales`. Then we have created `user_profile` for each regions(`Eu`,`JP`,`NA`) . And let's turn to hypotheses we rejected  `null` hypothesis for 2nd hypothesis. And accepted `null` hypothesis for 1st hypothesis. This means we can not prove or disprove the hypotheses are correct or not correct. Only thing that we can say that we can not accept or accept hypotheses.
