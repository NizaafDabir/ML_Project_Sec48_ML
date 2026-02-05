# Student Performance Prediction – Machine Learning Web App

This project is a Machine Learning based web application that predicts student performance based on academic and personal attributes.  
The model is trained using scikit-learn and deployed as a Flask web application on AWS Elastic Beanstalk.

---

## Live Deployment
The application is deployed on AWS Elastic Beanstalk and uses Gunicorn as the WSGI server.

---

## Machine Learning Overview
- Problem Type: Regression
- Objective: Predict student performance score
- Model trained using scikit-learn
- Model serialization using dill

---

## Tech Stack
- Backend: Flask
- Machine Learning: scikit-learn
- Data Processing: pandas, numpy
- Visualization: matplotlib, seaborn
- Server: Gunicorn
- Deployment: AWS Elastic Beanstalk
- Language: Python

---

## Project Structure
├── application.py # Flask application entry point
├── Procfile # Gunicorn startup configuration
├── requirements.txt # Project dependencies
├── model/ # Trained ML model files
├── src/ # Data processing and prediction logic
├── templates/ # HTML templates
├── static/ # CSS and JS files
└── README.md

---

## Deployment Notes
- Application runs using Gunicorn in production
- Procfile is required for Elastic Beanstalk:

- Entry point file must be named `application.py`

---

## Key Features
- End-to-end Machine Learning pipeline
- Clean and scalable project structure
- Production-ready Flask application
- Cloud deployment using AWS Elastic Beanstalk

---

## Future Scope
- Improve model accuracy
- Add advanced visualizations
- User authentication
- Database integration

---
