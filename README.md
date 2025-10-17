# Salary Prediction Web App

A machine learning-powered web app that predicts salaries based on user input such as years of experience and skill set, built using Flask and a trained regression model.

---

## Problem Statement

Job seekers and recruiters often struggle to estimate reasonable salaries considering education, experience, and skills. Manual estimations can be biased, unreliable, or guesswork-driven. This app leverages data-driven modeling to provide real-time, accurate salary predictions.

---

## Features

- User-friendly interface for entering years of experience and skills  
- Real-time salary prediction using a trained ML model (Random Forest)  
- Modular design facilitating easy improvements and deployment  
- Tested for edge cases such as zero experience, in-demand skills, and unusual education-skill combinations

---

## How It Works

### Training the Model
- Used salary dataset records to train a regression model  
- Model saved using `joblib` as `salary_model.pkl`

### Web Application
- Front end accepts user inputs: education, experience, skills  
- Flask backend loads the saved model and predicts salary in real-time  
- Displays predicted salary dynamically on the interface

---

## Results & Performance

- Achieved an R² score > 85% on test data  
- Prediction latency under 1 second  
- Robust against edge input scenarios

---

## Project Structure

├── notebooks/ # EDA and model training notebooks
├── data/ # Raw and cleaned datasets
├── models/ # Saved ML model files (.pkl)
├── app/ # Flask app source code and templates
├── docs/ # Documentation and presentations

---

## Author

Navneet Kumar Sharma  
[LinkedIn](https://www.linkedin.com/in/navneet-sharma-0a7a05228/) | [GitHub](https://github.com/NavneetsScripts)

---

> **Tags:** #Flask #MachineLearning #RandomForest #SalaryPrediction #WebApp

