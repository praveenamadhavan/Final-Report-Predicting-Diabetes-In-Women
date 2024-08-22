To predict Diabetes in Women using Machine Learning models

Business Summary
Diabetes in women is very common these days. So it is important to understand and be aware of the factors influencing the condition. Using predictive models in health care and clinical research can very well help in predicting the probability of occurrence or controlling the factors leading to it. 

Question
How can Machine learning models be used to predict the occurrence of Diabetes in women

Data source
https://www.kaggle.com/code/chanchal24/diabetes-dataset-eda-prediction-with-7-models/input?select=diabetes.csv
The dataset has 9 attributes of 768 volunteers researched. The feature characteristics are as follows

1. Outcome - Class variable (0 or 1) (have diabetes or not)
2. Age : Age in years
3. Blood Pressure : Diastolic blood pressure (mm Hg)
4. Glucose : Plasma glucose concentration a 2 hours in an oral glucose tolerance test 
5. BMI : Body Mass Index (weight in kg/(height in m)^2) 
6. Insulin : 2-Hour serum insulin (mu U/ml)
7. Pregnancies : Number of times pregnant
8. Skin Thickness : Triceps skin fold thickness (mm) 
9. Diabetes Pedigree : (Probability in family)


Methods used

Data preprocessing
. Clean the data (missing values)
. Remove irrelevant features , converting categorical to numerical values

Exploring ML models
. Logistic Regression
. Decision Trees
. K-Nearest neighbors
. Random Forest
. Support Vector Machines

Model Evaluation
Analyze and compare the performance of each model using accuracy score

Results

Feature importance : After looking at the feature importance from the Random Forest model, the main factors influencing the outcome are found to be the insulin level, Age and Glucose levels. This means the higher these factors are the probability increases. 
However other factors like Blood pressure, Diabetes Pedigree Function and Body Mass Index seem to have lesser influence on the outcome. 

Classifier model - Among the 6 classifier models analyzed, the Random Forest Classifier model performed better than the others with the highest accuracy score , 90%. Though the other models also predicted fairly well KNN having the lowest accuracy score of 85%

However the dataset used here is a relatively small sized one, with only 768 readings in total. May be with a big enough dataset, it can be expected that we would get better predictions results and influencing factors. 

