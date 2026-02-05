# Student Performance Prediction – Machine Learning Web App

This project is a Machine Learning based web application that predicts student performance based on academic and personal attributes.  
The model is trained using scikit-learn and deployed as a Flask web application on AWS Elastic Beanstalk.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## Live Deployment
The application is deployed on AWS Elastic Beanstalk and uses Gunicorn as the WSGI server.

[![Live Project](https://img.shields.io/badge/Live_Project-Click_Here-blue)]([https://book-recommender-caze.onrender.com](http://studentperformancesec48ml-env.eba-fpm7mm7y.us-east-1.elasticbeanstalk.com/))

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## Machine Learning Overview
- Problem Type: Regression
- Objective: Predict student performance score
- Model trained using scikit-learn
- Model serialization using dill

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Tech Stack
- Backend: Flask
- Machine Learning: scikit-learn
- Data Processing: pandas, numpy
- Visualization: matplotlib, seaborn
- Server: Gunicorn
- Deployment: AWS Elastic Beanstalk
- Language: Python

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Dataset Overview
The dataset consists of student academic and demographic records. Each row represents one student, and each column represents a specific attribute.

Target Variable:
- `math_score`: Student’s score in the mathematics exam (0–100). This is the dependent feature.

Independent Variables:
- `gender`: Gender of the student (male, female).
- `race_ethnicity`: Ethnicity group of the student (Group A, B, C, D, E).
- `parental_level_of_education`: Highest education level of the student’s parent(s).
- `lunch`: Type of lunch program (standard or free/reduced).
- `test_preparation_course`: Whether the student completed a test preparation course (completed or none).
- `reading_score`: Student’s score in the reading exam (0–100).
- `writing_score`: Student’s score in the writing exam (0–100).
- 
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Deployment Notes
- Application runs using Gunicorn in production
- Procfile is required for Elastic Beanstalk:

- Entry point file must be named `application.py`

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Key Features
- End-to-end Machine Learning pipeline
- Clean and scalable project structure
- Production-ready Flask application
- Cloud deployment using AWS Elastic Beanstalk

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## Future Scope
- Improve model accuracy
- Add advanced visualizations
- User authentication
- Database integration

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nizaaf-dabir-524596203/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NizaafDabir)
