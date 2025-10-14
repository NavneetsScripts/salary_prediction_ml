Salary Prediction Web App

Problem:

It's hard for both job searchers and recruiters to figure out what a reasonable compensation is for a job these days, depending on things like education, experience, and talents.  Estimating by hand can be skewed, unreliable, or reliant on guessing instead of data.

We used Flask to make a web app that uses machine learning to guess how much money someone will make based on

-Years of experience
-Set of skills

Features: An easy-to-use interface for predicting salaries

 Inference in real time using a trained ML model (like Random Forest)

 Modular design makes it easy to deploy or improve

 Tested on edge scenarios to make sure it works well

 How It Works: 
 Training the Model

 We used a dataset comprising salary records to construct a regression model.

 Used joblib to save the model as salary_model.pkl.

 Web App:

 Users enter their education, experience, and talents on the front end.

 The Flask backend loads the trained model and makes salary predictions in real time.

 The online interface shows the prediction again.

Results 
Accuracy: Got a test data R² score of over 85%.
Response Time: Prediction in real time takes less than a second.

Checked edge situations like:
No experience
Many abilities that are in high demand
Strange pairings of education


This project aims to build a machine learning model to predict salaries based on input features such as experience, job role, and more. Built using Python, Scikit-learn, and Flask.
Project Structure
- `notebooks/`: Colab notebooks for EDA, modeling
- `data/`: Raw and cleaned datasets
- `models/`: Saved pickle files
- `app/`: Flask app and templates
- `docs/`: Work order and presentation

Author
Navneet Kumar Sharma 

