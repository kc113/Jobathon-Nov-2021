## Problem Statement:

You are working as a data scientist with HR Department of a large insurance company focused on sales team attrition. Insurance sales teams help insurance companies generate new business by contacting potential customers and selling one or more types of insurance. The department generally sees high attrition and thus staffing becomes a crucial aspect. 
To aid staffing, you are provided with the monthly information for a segment of employees for 2016 and 2017 and tasked to predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not, given:

1. Demographics of the employee (city, age, gender etc.)
2. Tenure information (joining date, Last Date)
3. Historical data regarding the performance of the employee (Quarterly rating, Monthly business acquired, designation, salary)

## Feature Engineering:

•	From the initial inspection of the data, it is quite evident that the data is a time-series data. So, the first task is to convert it to a supervised learning problem by cleaning the data and creating/extracting relevant features (including the target variable).

•	Important features created from the dataset are ‘Service period’, ‘Promoted by’, ‘Last Business Value’, and ‘Attrition’.


## Model Building:

Ada Boost Classifier is used for modeling.

## Evaluation Metrics

The f1_score on the validation data (Dec-2016 month) using the Ada Forest Classifier is ~0.69.
