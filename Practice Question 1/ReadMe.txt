!!! ReadMe !!!

We elected to use a dataset called "Titanic" from Kaggler, the dataset has information about people who were aboard the Titanic in 1917, and the predictive model predicts survivors in the future based on different factors.


We firstly imported libraries such as pandas, numpy, matplotlib and seaborn as they will be used for writing, deploying and visualizing the findings from the dataset.


The data is extracted from a file called "Titanic-Dataset.csv" so Titanic was created as the dataframe, hence it is referred to as "df1"


We used the "info()" funtion to get more insight on the data types found in the different columns in the dataset.


Then we continued to use the "isna" and "sum" functions to find columns which have missing values and the number of values which may be missing from each column


The "Age" column had 177 missing values, so we filled them with the median, "Cabin" column had 687 missing values so the column was dropped, "Embarked" had 2 missing columns so with filled it with the mode.


Because the model has to predict survivor's, we grouped the data using the "Sex and Survived" columns.


Because Normalization is only possible while using numerical columns and not strings, we used the following numerical columns for normalization: "PassengerId, Survived, Pclass, Age, SibSp, Parch, Fare"


The same columns were used to create the Classification Regression on the "X" variable, while the "Survived" column was used for the "Y" variable, the chosen model was the Logistic Regression model as it will either say "Yes" if a person survived or "No" if they did not




 