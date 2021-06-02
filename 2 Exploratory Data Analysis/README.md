# Research on car sales ads

### Goal of the project:
Hundreds of free advertisements for vehicles are published on at Crankshaft List's site every day.

Need to study data collected over the last few years and determine which factors influence the price of a vehicle. 

### Project plan:
1. Open the data file and study the general information. 
2. Data preprocessing
3. Make calculations and add them to the table
4. Carry out exploratory data analysis
5. Overall conclusion

### Used libraries:
1. **Pandas**: used for `data preporecessing`, `data analyzing` and partially `data visualization`.
2. **matplotlib.pyplot**: used as an helper library for visualize `graphs`.

### Conclusion drawn from the project:
In conclusion, on the price of the vehicle mostly influences `model_year`. And `is_4wd`,`condition`,`avg_mileage` and `cylinders` factors impacts on decreasing order correspondly. And `days_listed`,`posted year and month` and `weekday` factors impacts very very small, which means we can ignore them. The `distance` that car driven and `age` of car will impact vice versely which means the higher this values the price will be lower