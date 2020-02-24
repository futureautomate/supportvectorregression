# Support Vector Regression Machine Learning
This example explains working with polynomail regression and concrete dataset.
Link to the dataset - https://www.kaggle.com/maajdl/yeh-concret-data

 Support Vector regression is used for non-linear regression problems.

### Steps:

## 1) Load the Data:
1. Load the data in pandas.
2. This dataset will not get coloumns here but we can add that easily
3. Check the notebook for the code.

## 2) Clean The Data:
 1. As its the easiest problem the dataset doesn't have any Missing or duplicate values.
 2. Althouth there's a scope of work everywhere so we can check for understanding.
 
 ## 3) Feature Selections:
 1. With basic method of correlection we will first try to judge which features we can drop.
 2. We can also play with different method and get different predication scores.
 3. I did try the univariat feature selection.
 4. Ultimately the score was same so, revert back....
 
 ## 4) Split the data:
 1. We need to split the data for training and testing.
 2. The data is split into 70% training and 30% testing.
 
 ## 5) Fit the model:
 1. we use the liner regression model to get predicsitons.
 2. after the fit, use predict method for prediction
 3. To create a regressor object in SVR there are few parameters need to be know.
 4. The first is type of kernal.... linear, rbf, polynomial
 5. Degree is for polynomail kernel
 6. C is the type of regularization.
 
 ## 6) Prediction score:
 1. there are many ways to check the goodness of model
 2. I have used r2_score to check and the model worked fine.
 
 
 The kerner didnt work well on this data set as it is kind of linear. You can try it with different datasets and see how it works. Try SVR for all the kernals and see how the scores changes.
 Check the code and use for more improvement and share...!!!!!
 

