# Exploratory Data Analysis With Python: Cardiovascular Disease Risk Prediction

This project explores a dataset containing information about factors that may contribute to the risk of cardiovascular disease (cardio), such as age, gender, height, smoking status, and blood pressure in Python. The goal of this analysis is to gain insights into the relationships between these factors and the likelihood of developing CVD.
The risk of cardiovascular disease (CVD) is a serious health threat to human society worldwide. The use of machine learning methods to predict the risk of CVD is of great relevance to identify high-risk patients and take timely interventions. Cardiovascular diseases(CVD) are a group of heart and vascular diseases, namely coronary, cerebrovascular, and rheumatic heart. It has been reported that more than 17.9 million patients die each year worldwide due to heart and vascular disease.

## Dataset

The dataset used in this analysis  can be accessed [here](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
It contains the following columns:
- Age | Objective Feature | age | int (days)
- Height | Objective Feature | height | int (cm) |
- Weight | Objective Feature | weight | float (kg) |
- Gender | Objective Feature | gender | categorical code |
- Systolic blood pressure | Examination Feature | ap_hi | int |
- Diastolic blood pressure | Examination Feature | ap_lo | int |
- Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
- Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
- Smoking | Subjective Feature | smoke | binary |
- Alcohol intake | Subjective Feature | alco | binary |
- Physical activity | Subjective Feature | active | binary |
- Presence or absence of cardiovascular disease | Target Variable | cardio | binary |
- All of the dataset values were collected at the moment of medical examination.
## Analysis

The EDA process included the following steps:

1. **Data Cleaning**: Handling missing values, removing duplicates, and correcting data types.
2. **Exploratory Analysis**: Calculating summary statistics, visualizing distributions, and identifying outliers.
3. **Feature Engineering**: Creating new features, converting age from days to years, to enhance analysis.
4. **Correlation Analysis**: Examining correlations between variables to understand their relationships.
5. **Visualization**: Creating visualizations, such as bar charts, pie charts and scatter plots, to explore the data.

## Findings

Some key findings from the analysis include:

- There is a positive correlation between age and the risk of CVD.
- Smokers tend to have a higher risk of CVD compared to non-smokers.
- Blood pressure levels are also positively correlated with the risk of CVD.

## Conclusion

This exploratory analysis provides valuable insights into the factors that may contribute to the risk of cardiovascular disease. Further analysis, such as predictive modeling, could be conducted to develop a more accurate risk prediction model.

## Future Work

- Build a predictive model to predict the risk of CVD based on the available factors.
- Explore additional factors, such as cholesterol levels and diet, that may influence the risk of CVD.

## Repository Structure

- **data**: Contains the dataset used in the analysis.
- **notebooks**: Contains Jupyter notebooks with the EDA process.
- **visualizations**: Contains visualizations generated during the analysis.
- **README.md**: This file providing an overview of the project.

---

Feel free to customize this template to fit your project's specific details and findings.
