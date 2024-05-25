# ML_Algorithm-Linear_Regression
In this notebook, we have bult the Linear Regression Model for Insurance datasets. This Insurance datasets include dependent variable like 'age', 'sex', 'bmi', 'children', 'smoker', 'Claim_Amount', 'past_consultations', 'num_of_steps', 'Hospital_expenditure', 'Number_of_past_hospitalizations', 'Anual_Salary', 'region' etc. While, the target variable is 'Charges' columns. We have built the model
to predict the charges columns. Please go through the Steps I have used to built this model.
## Table Of Content
### Importing the Library
I have imported the libraries like numpy and pandas to do the basic data analysis of the given datasets.
### Uploading the Dataset
I have uploaded the dataset from the google drive to my colab notebook on which I have built this model. You can find the similar dataset in the Kaggle.
### Exploratory Data Analysis
In this process, we have built the graphs and visual content to understand the data. We have used the pandas for data wrangling purpose. Pandas has been very useful tools to understand the nature of independent
and dependent columns. Also they have useful for manipulating the data so that it can useful for building the models.
### Data Cleaning
I have used the basic statistic method for the data cleaning. We have removed the null values, outliers in the data.
### Data Preprocessing
I have used 'Variance Inflation Factor' technique to remove the unwanted columns that can impact the model accuracy.
### Building the model
After the VIF has been done, I have splitted the data in train and test data. It will include x_train, x_test, y_train, y_test. x_train and y_train has 80% of the data. while x_test and y_test have remaining 20% of the data. I have imported the Linear regression algorithm from scikit-learn and used it to build the model by using the x_train and y_train data.
### Predicting the model efficiency
I have import r2 score from sklearn and used to predict it the model accuracy. We can also RMSE to predict the efficacy of Linear Regression Model
