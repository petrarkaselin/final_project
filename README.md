&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; ![logo](https://github.com/petrarkaselin/final_project/blob/master/slides/ironhack_logo.png)

### Author: Tatyana Tarasova

# Attrition prediction for **SAP SuccessFactors**
**SAP** is a leading enterprise software company that provides integrated business solutions, including ERP (Enterprise Resource Planning), to help organizations streamline processes, manage data, and optimize business operations.

**SAP SuccessFactors** is a cloud-based human capital management (HCM) suite offered by SAP, focusing on optimizing HR processes.3. It encompasses a range of modules such as payroll system, employee performance, learning management, on- and offboarding process and workforce analytics.

![successfactors](https://github.com/petrarkaselin/final_project/blob/master/slides/04.jpg)

#### Importance of attrition prediction:
- Impact productivity, morale and costs.
- The main reason of emplyee departures is voluntary termination. 
- Helps by workforce planning, cost reduction, improving worplace culture. 

![reasons](https://github.com/petrarkaselin/final_project/blob/master/slides/08.jpg)

#### Goal
The goal of the project was to create a presentation visualizing the new feature for **SAP SuccessFactors**.

#### Object
To create an algorithm that takes the employee data from the HCM database and gives a prediction, if the chosen emloyee can quit in the near future.

![quit](https://github.com/petrarkaselin/final_project/blob/master/slides/05.jpg)

#### Dataset: [IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

#### Methods:
##### Data preparation:
- Checking the variables for the multicollinearity:
    - Correlation matrix
    - VIFs
- Standardization of numerical variables:
    - Standard Scaler
    - MinMax Scaler
- Handling outliers 
    - Zscore 
- Dropping all unnecessary features and outliers

##### Supervised machine learning:
- Balancing the data:
    - unbalanced (original) data
    - SMOTE
    - Random Under Sampler
    - Near Miss
- Models:
    - Logistic regression
    - KNN model
    - Decision tree
- Meta model:
    - Stacking method including three models
- Validation of the models:
    - Accuracy
    - Precision
    - Recal
    - F1 score
    - Confusion matrix
    - Cohen's Kappa
    
![stacking](https://github.com/petrarkaselin/final_project/blob/master/slides/15.jpg)
![scores](https://github.com/petrarkaselin/final_project/blob/master/slides/16.jpg)

#### Conclusion:
The new feature **'Attrition prediction'** will help managers to develop prevention measures to decrease the employee turnover.

Examples of these measures can be:
- Retension strategies
- Personalized interventions
- Employee Engagement Initiatives