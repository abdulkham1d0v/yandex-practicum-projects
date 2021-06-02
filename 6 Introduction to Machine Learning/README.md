# Predicting Telecom operator's Users Behavior

### Goal of the project:
This project is going to about `ML`. Megaline company which we worked on SDA chapter wants to develop model that will recommend to user one of `Ultra` and `Smart`. To develop this model we will use dataset which consists user behavior and will stick to plan which is located below. 


### Project plan:
1. **Opening and looking through the data file**
2. **Splitting the source data into a training set, a validation set, and a test set.**
3. **Investigating the quality of different models by changing hyperparameters**
4. **Checking the quality of test set**
5. **Additional task**
6. **General conclusion**

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **sklearn.model_selection**: for splitting data into `train`, `test` and `validation` sets.
3. **sklearn.metrics**: for estimating `accuracy_score`, `recall` and `precision`
4. Then used **DecisionTreeClassifier**, **RandomForestClassifier** and **LogisticRegression** models for getting `higher` accuracy.


### Conclusion drawn from the project:
Until there we have made lots of things. We have looked data. Then we have splitted data. After that we have trained different models  and checked their accuracy. Then we picked up best model and it's accuracy were about `0.793`. Then we have checked precision and recall of our model. By categorizing columns we can get higher accuracy score. For example we can categorize columns into 5 category by `0-4`. Then we will get accuracy about 1 or 1.