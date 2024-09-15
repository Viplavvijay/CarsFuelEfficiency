# CarsFuelEfficiency
This project is a web application developed using Flask that predicts vehicle miles per gallon (MPG) based on user-uploaded CSV files. The application integrates a pre-trained machine learning model to provide real-time predictions and displays the results in a user-friendly HTML format.


![Alt text](https://github.com/Viplavvijay/CarsFuelEfficiency/blob/main/carsfeff.png)




Flask-based Machine Learning Web Application- CARS FUEL EFFICIENCY
Overview
This project is a web application developed using Flask that predicts vehicle miles per gallon (MPG) based on user-uploaded CSV files. The application integrates a pre-trained machine learning model to provide real-time predictions and displays the results in a user-friendly HTML format.

Features
User Input: Allows users to upload CSV files containing vehicle data.
Real-time Predictions: Utilizes a pre-trained machine learning model to predict MPG for the uploaded data.
Data Processing: Employs pandas for data manipulation and transformation.
Database Integration: Uses SQLAlchemy to connect to a MySQL database for storing and retrieving prediction results.
Deployment: Containerized using Docker and deployed with gunicorn for production readiness.
Technologies Used
Programming Languages: Python
Web Framework: Flask
Machine Learning: pickle, joblib
Data Processing: pandas
Database: SQLAlchemy, MySQL
Deployment: Docker, gunicorn
Getting Started
Prerequisites
Docker
Python 3.8+
MySQL (optional, for database integration)
Installation
Clone the repository:

Install the required Python packages:

Build the Docker image:

Run the Docker container:

Usage
Open your web browser and navigate to http://localhost.
Upload a CSV file containing vehicle data.
View the predicted MPG results displayed on the web page.
