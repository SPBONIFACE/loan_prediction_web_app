# Loan prediction web application
Deployment of a loan prediction model on the web

As part of the Dphi Machine Learning bootcamp - advanced track, I had to create a web application for a loan application prediction model (assignment 3).

Link to the web application: https://spb-loan-prediction-app.herokuapp.com/

This application was deployed online using **Flask** and **Heroku**.

This was my first attempt at deploying a machine learning model.

I decided to start things small, using a plain vanilla **Logistic Regression** model with no preprocessing steps except for missing value imputation and encoding of categorical variables. 

Initially my model included several preprocessing steps (scaling, OneHot encoding, feature engineering). Those steps increased marginally model performance. However, my focus was not on achieving the best performance / accuracy possible but on creating a model that could be easily deployed.

For UI/Front end, I used a html template available on codepen.io and designed by Aaron Cuddeback @ Gymratpacks https://codepen.io/gymratpacks

There is still lot of room for improvement.

**Next steps:**
-	Use a more complex model (RandomForest, SVC, XGBoost, LightGBM or Ensembles)
-	Improve model performance using RandomizedSearch and GridSearchCV
-	Include a preprocessing pipeline in the deployed model code using BaseEstimator and TransformMixin that will also apply to new unseen data 

Note:
Dphi is an association whose aim is to democratize Data science. They organize free bootcamps. Their approach does not rely on traditional academic teaching methods but on community learning and facilitating hands-on teaching with just enough theory to get the intuition behind key concepts.
https://dphi.tech/

