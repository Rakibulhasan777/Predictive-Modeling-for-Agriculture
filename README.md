# Predictive-Modeling-for-Agriculture

## Project Overview 
### Sowing Success: How Machine Learning Helps Farmers Select the Best Crops
![farmer_in_a_field](https://github.com/Rakibulhasan777/Predictive-Modeling-for-Agriculture/assets/109708414/2fae6a5f-711c-425d-957d-c981ed6723c4)
Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints. 
Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield. 
This Data Analysis project aims to help a farmer to select the best crop for his field. Due to budget constraints, the farmer explained that he could only afford to measure one out of the four essential soil measures:
  * `Nitrogen` content ratio in the soil
  * `Phosphorous` content ratio in the soil
  * `Potassium` content ratio in the soil
  * `pH` value of the soil

## The Data 
The dataset used in this project is called `soil_measures.csv`, which contains:

- `"N"`: Nitrogen content ratio in the soil
- `"P"`: Phosphorous content ratio in the soil
- `"K"`: Potassium content ratio in the soil
- `"pH"` value of the soil
- `"crop"`: categorical values that contain various crops (target variable).

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the `"crop"` column is the optimal choice for that field.  

In this project, I will build multi-class classification models to predict the type of `"crop"` and identify the single most importance feature for predictive performance.

## Prerequisites 
  * Python 3.6 or higher [Dowload Here](https://www.python.org/downloads/)
  * Pandas
  * LogisticRegression from sklearn.linear_model
  * train_test_split from sklearn.model_selection
  * metrics from sklearn

## Steps to complete 
  * Read the data into a pandas DataFrame and perform exploratory data analysis
  * Split the data
  * Evaluate feature performance
  * Create the best_predictive_feature variable

## Results/ Findings 
|Best Perdictive feature |Feature performance |
|------------------------|--------------------|
|`K` |0.23896974566001802 |
