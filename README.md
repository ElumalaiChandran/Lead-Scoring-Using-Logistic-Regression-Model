# Lead-Scoring-Using-Logistic-Regression-Model

- Problem Statement :
	- An education company named X Education sells online courses to indutry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 
	- X Education wants to find out the leads that are most likely to convert into paying customers. The company requires to build a model and to assign a lead score to each of the leads such that the customers with higherlead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

- Requirement/Objective:
The company wants to know::
	- Build a  logistic regresion model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. 
	- A higher score would mean that the lead is hot and is most likely to converted.
	- A lower score would mean that the lead is cold and will mostly not get converted.

## Lead Scoring Prediction - Solution
The solution is divided into the following sections:
- Understanding the dataset  & EDA Building  
- Data Preparation 
- Model Building 
- Model Evaluation

## Data understanding and Exploration
Data Understanding and exploring the data is very important steps in any of the Predictive models.Exploring the dataset.

- Row Count
- Column Count
- Check for Outliers any
- Check for missing/null values
- Duplicates
- Perform EDA and get to know correlation of the variables to the independent variables
- Thus, while building the model, we'll have to pay attention to multicollinearity (especially linear models, such as linear and logistic regression, suffer more from multicollinear).

## Data Preparation 
- Create Dummy Features 
- Perform Train-Test Split 
- Perform Scaling 

## Model Building 
- Using stat model the model is build for the top 15 variables. 
- Confusion matrix is build for the model and analyzed the Accuracy, Sensitivity, Precision, Recall. 
- VIF score is calculated for the variables and eliminated the variables whose value is more than 5.

## Model Evaluation 
- ROC Curve 
	- It shows the trade off between sensitivity and specificity (any increase in sensitivity will be accompanied by a decrease in specificity)
- Optimal Cut off Point 
	- For the different probability from 0.0 to 0.9 calculated the Accuracy, Sensitivity, Precision,Recall. 
	– Line chart is plotted for Accuracy, Sensitivity,Precision, Recall and found the actual cut of point.
- Predictions on the test set
  - Using the train model the values are predicated for the test data set.
  - Accuracy, Sensitivity, Precision, Recall is calculated for the test modal.

