# Logistics-Regression
A first pass a logistics regression
This is a first pass at logistics regression. It uses a Kaggle database using the likelihood of suffering from diabetes given a list of 
life-characteristics. The Outcome is the dependent characteristic at 1/0 w/ the remaining variables as the components of the model
The code itself is based on a YouTube tutorial by Denisa Marcisovska adjusted for the difference in the data Denisa used in her model
as compared to the diabetes model, specifically that the Pima dataset is all int or float64 columns while the Churn dataset used by 
Denisa has string variables necessitatin the use of LabelEncoder and OneHotEncloder from sklearn.preprocessing and sklearn.ColumnTransformer
I'm going to try to find a dataset where those features can be used.
Lastly the boxplot doesn't look very good with this dataset or at least for the columns that I tried to use
