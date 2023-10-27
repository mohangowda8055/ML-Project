## End to End Machine Learning Project
The Machine Learning Student Exam Performance Indicator is an application designed to predict a student's math exam score based on several factors. These factors include the student's gender, race/ethnicity, parental level of education, lunch type, whether they completed a test preparation course, and their scores in writing and reading exams.

The application uses machine learning algorithms. These algorithms have been trained on a dataset that includes historical student information and math exam scores. During training, the algorithms learn the patterns and relationships between the input factors (gender, parental education, etc.) and the math scores.

First I performed EDA and Model Training in Jupyter Notebook, later I followed standard project structure to develop Student Exam Performance Indicator App using Visual Studio Code IDE and Flask framework.
### Following Steps were performed:
#### Data Ingestion - 
I collected data from a csv file, later train test split was performed in Data Ingestion component. 
#### Data Transformstion - 
Handling missing values in numerical and categorical features, standard scaling the numerical features and encoding the categorical features. Later, I applied preprocessing object on test and training dataframe.
#### Model Training - 
Splitting train and test input data, applied various algorithms and evaluated models using r2 score.
#### Hyperparameter Tuning - 
Hyperparameter tuning was also performed to train the model.
#### Prediction Pipeline - 
Applied the same preprocessing steps (scaling, encoding, etc.) to new data that were applied to the training data. Used the trained model to make predictions on the preprocessed new data.

----------
![ML1](https://github.com/mohangowda8055/ML-Project/assets/125982691/8ef0aa84-2207-48ac-aab9-edaf0a6b3c96)
-----------
![ML2](https://github.com/mohangowda8055/ML-Project/assets/125982691/e95f4db5-c002-433a-925a-9509f9655387)
