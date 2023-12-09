# Description about the Housing Prices Project

First step of to filter the project is to filter the unessecary coloumns, hence the  country, statezip, street , date, city, view, waterfront, sqft_above, sqft_basement, 
condition coloumns were dropped. 

Then the train test split were performed , where there is a training model and a testing model. In order to find the R-squared Train Score , R-squared Test Score, Mean Squared Error of Train and Mean Squared Error of Test. R-squared score is to show how well the data fits into the regression model. Meanwhile Mean Squared Error is to show how close the data is from the regression model.

Random Forest regression is also being made in order to improve the accurracy of the model. However, the storage and the capacity is execptionally large. Therefore we set the estimators to 1200 in order to minimize the computer workload.

we also set some dropdown menus for the html. Providing a better interface for users to find the data for the respective housing information.

