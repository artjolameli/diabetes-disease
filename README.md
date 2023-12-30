Diabetes Hospital Readmission Analysis

This project aims to analyze hospital readmissions related to diabetes using the "Diabetes 130-US hospitals for years 1999-2008" dataset from the UCI Machine 
Learning Repository https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F296%2Fdiabetes%2B130-us%2Bhospitals%2Bfor%2Byears%2B1999-2008. 
The dataset was chosen due to the widespread and critical nature of diabetes as a health condition, with the goal of gaining insights into healthcare management and outcomes.

Hypotheses

Based on the dataset, the following hypotheses were proposed and explored:

Medication Adherence: Higher adherence to medication leads to lower readmission rates.
Inpatient Visits: Greater number of inpatient visits increases the likelihood of readmission.
Age: Younger patients are more likely to be readmitted due to fewer underlying health issues.
Analysis

The analysis covers various aspects of the dataset, including model performance, feature importance, and the impact of feature selection. 
Several machine learning models were trained and evaluated, with the Random Forest and Linear Regression models being highlighted. 
The heatmap of probability for the Random Forest model provided insights into the model's confidence across different feature values.

Results

Model Performance: The models achieved varying levels of accuracy.
Feature Selection: We filtered out weaker features and used only the strongest features ('readmitted' and 'num_medications') in further analysis.
Comparison of Models: The Linear Regression model showed slightly better performance than the Random Forest model, although the difference was marginal.
Conclusion

The analysis provides valuable insights into factors influencing hospital readmissions for diabetes patients. Future steps could involve refining the models or gaining a deeper understanding of the underlying patterns in the data.
