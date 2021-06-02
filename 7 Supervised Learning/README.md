# Predicting Bank customers Behavior


### Goal of the project:
Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank. 
Build a model with the maximum possible `F1 score`.  To pass the project, you need an F1 score of at least **0.59**.  Check the F1 for the test set.
Additionally, measure the **AUC-ROC** metric and compare it with the **F1**.


### Project plan:
1. **Downloading and preparing the data**
2. **Examining the balance of classes.**
3. **Improving the quality of the model**
4. **Performing the final testing**
5. **General Conclusion**

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **matplotlib.pyplot**: used for helping with `data visualization`
3. **numpy**: used for setting a `arange` for  `for loop`
4. **sklearn.preprocessing**: used for `scaling` features
5. **sklearn.utils**: used `shuffle` for `upsampling` and `downsampling` technique.
6. **sklearn.model_selection**: for splitting data into `train`, `test` and `validation` sets.
7. **sklearn.metrics**: for estimating `accuracy_score`, `recall` and `precision`, `f1_score`, also for `roc_curve`,`roc_auc_score`
8. Then used **DecisionTreeClassifier**, **RandomForestClassifier** and **LogisticRegression** models for getting `higher` accuracy.


### Conclusion drawn from the project:
In conclusion, we have made lots of things. Preprocessed data, tried to improve imbalance problems. Then we used different model, and at the end we got **0.606** `f1_score` with final model. Also we have plotted `ROC curve` and calculated area under curve. It was bigger than f1_score. To sum up `Linear Regression` model was not well enough for this task. As we observed `RandomForestClassifier` was best model for this task