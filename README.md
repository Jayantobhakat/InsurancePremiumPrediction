## END TO END PREMIUM PREDICTION PROJECT


PROBLEM STATEMENT:
The goal of this project is to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather han the ineffective part.

DATASET: The datset is taken from a Kaggle. You can download the dataset from https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction

URL: https://premiumprediction.azurewebsites.net/predictdata

APPROACH:
Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the personal for health insurance.
- Data Exploration : Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
- Exploratory Data Analysis : Plotted different graphs to get more insights about dependent and independent variables/features.
- Feature Engineering : Numerical features scaled down and Categorical features encoded.
- Model Building : In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
i.Linear Regression
ii.Decision Tree Regressor
iii.Random Forest Regressor
iv.Gradient Boosting Regressor
v.XGBoost Regressor
vi.KNN
- Model Selection : Tested all the models to check the RMSE & R-squared.
- Pickle File : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
- Webpage &Deployment : Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.

  LIBRARIES USED:
-> pandas
-> numpy
-> seaborn
-> -e .
-> scikit-learn
-> matplotlib
-> Flask
-> dill
-> seaborn
-> catboos


  CONCLUSION
This project successfully demonstrates the application of machine learning in predicting medical insurance premiums. The model's performance indicates its potential in aiding individuals to make informed healthcare decisions. While the model is a powerful tool, it complements, not replaces, professional advice. Future work could expand this model, exploring more variables and sophisticated techniques, further enhancing its predictive power. Ultimately, this project highlights the transformative potential of data science in healthcare and insurance industries.t
-> xgboost
