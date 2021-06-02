# Protecting client's data(The Sure Tomorrow)

### Goal of the project:
The Sure Tomorrow insurance company wants to protect its clients' data. Your task is to develop a data transforming algorithm that would make it hard to recover personal information from the transformed data. Prove that the algorithm works correctly

The data should be protected in such a way that the quality of machine learning models doesn't suffer. You don't need to pick the best model.




### Project plan:
**1. Data downloading**

**2. Multiplication of matrices**

**3. Transformation algorithm**

**4. Algorithm test**

**5. Conclusion**


### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing`.
2. **numpy**: used for matrix operations.
3. **sklearn.metrics**: for estimating `r2_score`.
4. **sklearn.model_selection**: used `train_test_split` for splitting data into `train` and `test` sets.
5. Then used **LinearRegression** for this project


### Conclusion drawn from the project:
According to our findings `r2_score` is same for original and transformed datasets. And difference between them very close to 0 we surely can neglect this value. This states that our derived proof is true! 


