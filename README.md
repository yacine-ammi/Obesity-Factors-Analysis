# Overview
## Objective
The objective of the study is to identify the factors that affect obesity the most. To achieve this, three approaches are used: PCA, classification, and regression. 

<a href="https://nbviewer.jupyter.org/github/yacine-ammi/Obesity-Factors-Analysis/blob/main/obesity-factors-analysis.ipynb" target="_blank">
    <img src="https://img.shields.io/badge/render-nbviewer-blue.svg" alt="Open In nbviewer"/>
</a>

<a href="https://www.kaggle.com/code/ammiyacine/obesity-factors-analysis" target="_blank">
    <img src="https://img.shields.io/badge/Open%20In-Kaggle-blue" alt="Open In Kaggle"/>
</a>

<a href="https://www.github.com/yacine-ammi/Obesity-Factors-Analysis/blob/main/obesity-factors-analysis.ipynb" target="_blank">
    <img src="https://img.shields.io/badge/Open%20in-GitHub-blue" alt="Open In Github"/>
</a>

### Approaches

> - PCA is used to identify the factors that contribute the most to obesity.
> - Classification is used to identify the most important predictors of obesity.
> - Regression is used to identify the factors that contribute the most to an individual's BMI.

### Interpretation

To interpret the results, the SHAP approach is used in both classification and regression. SHAP values are used to explain the contribution of each feature to the target variable, providing a deeper understanding of the contribution of each feature to obesity.

### Overall

Overall, these three approaches work together to identify the most important factors that affect obesity. PCA identifies the most important features, classification identifies the most important predictors of obesity, and regression identifies the factors that contribute the most to an individual's BMI. The interpretation of the results using the SHAP approach provides a more detailed understanding of the contribution of each feature to obesity.

## About the dataset
This dataset include data for the estimation of obesity levels in individuals from the countries of Mexico, Peru and Colombia, based on their eating habits and physical condition. 77% of the data was generated synthetically using the Weka tool and the SMOTE filter, 23% of the data was collected directly from users through a web platform.

The data contains 17 attributes and 2111 records, the records are labeled with the class variable NObesity (Obesity Level), that allows classification of the data.
## Results
After conducting PCA, Classification, and Regression analyses on the UCI Obesity Dataset, it can be concluded that several factors have been identified as significant predictors of obesity. The results show that family history with overweight, age, frequency of consumption of vegetables, and gender are the most important factors that affect and can predict obesity.

