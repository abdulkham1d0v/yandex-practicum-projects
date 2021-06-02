# Analyzing Telecom operator's Plans

### Goal of the project:
We are working analyst in a telecom operator Megaline.And company offers its clients two prepaid plans.We have data of small client selection. 

Based on this data we must test hypothesis which are given on the description

### Project plan:
1. Opening data files and studying general information
2. Preprocessing data
3. Analyzing data
4. Test the hypothesis
5. Drawing overall conclusion

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **matplotlib.pyplot**: used as an helper library for visualize `graphs`.
3. **numpy**: used for calculating `mean`,`variance` and `standard deviation`
4. **scipy**: used for testing hypotheses.

### Conclusion drawn from the project:
We have made lots of analysis on a data and we have found lots of information about a data  which we had. As wee see above `call_duration`'s average value in `ultimate` equals to 409.08 minutes and `surf`'s equals to 421.42 minutes. And users which are using `ultimate` plan sends about 46 messages and `surf`'s users sends about 49 messages each month on average.And both plans users uses around 39 gb of data each month on average.And we can say that they have a quite similar distribution on using internet monthsly. Let's turn to hypotheses. When testing first hypothesis we get rejected from `null` and `alternative` hypotheses. This means we can not prove or disprove plans' profits equal or not equal. Only thing that we can say that we can not accept hypotheses. Let's turn to second one. Also, only thing that we would say we will accept `null` and `alternative` hypothesis.This means that, `average profit` from users in NY-NJ area different from that of the users from other regions