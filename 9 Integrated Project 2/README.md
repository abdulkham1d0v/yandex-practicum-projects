# Gold Refinery project

### Goal of the project:
Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry.
The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification.
The model will help to **optimize the production** and **eliminate unprofitable parameters**.




### Project plan:
**1. Prepare the data**

    1.1. Open the files and look into the data.
        
    1.2. Check that recovery is calculated correctly. Using the training set, calculate recovery for the    rougher.output.recovery feature. Find the MAE between your calculations and the feature values. Provide findings.
    
    1.3. Analyze the features not available in the test set. What are these parameters? What is their type?
    
    1.4. Perform data preprocessing.
    
**2. Analyze the data**

    2.1. Take note of how the concentrations of metals (Au, Ag, Pb) change depending on the purification stage.
    
    2.2. Compare the feed particle size distributions in the training set and in the test set. If the distributions vary significantly, the model evaluation will be incorrect.
    
    2.3. Consider the total concentrations of all substances at different stages: raw feed, rougher concentrate, and final concentrate. Do you notice any abnormal values in the total distribution? If you do, is it worth removing such values from both samples? Describe the findings and eliminate anomalies.
    
**3. Build the model**

    3.1. Write a function to calculate the final sMAPE value.
    
    3.2. Train different models. Evaluate them using cross-validation. Pick the best model and test it using the test sample. Provide findings.

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **numpy**: used for getting a `abs` when estimating `z-score`
3. **matplotlib.pyplot**: used for helping with `data visualization`.
4. **scipy**: used for estimating `zscore`.
5. **sklearn.metrics**: for estimating `mean_absolute_error`.
6. **sklearn.preprocessing**: for scaling features.
7. **sklearn.model_selection**: used `GridSearchCV` and `cross_cal_score` libraries for the searching best model parameters.
8. Then used **LinearRegression**, **DesicionTreeRegressor**, **RandomForestRegressor** models for getting highest accuracy.


### Conclusion drawn from the project:
We have made lots of things to reach here. Firstly opened data and looked into it. then we have performed data preprocessing. After that we have made analyzing. Found outliers and eliminated them. Then we found best model using train set. For this business task **RandomForestRegressor** was best. And we got `sMape` ***6.443***  And we recommend to `Zyfra` to look for other models. Because `time is money` in business. And *RandomForestRegressor* model took about `15 - 20 minutes` in our case. So, it will take lots of time in real world business

