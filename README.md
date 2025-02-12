Medical Recommendation System

Overview
The Medical Recommendation System is a web application powered by Python, Flask, and Machine Learning, which predicts diseases based on the symptoms stated by the user. The system suggests medications, precautions, diet plans, and workouts to manage the predicted disease.

Features
Disease Prediction: The users can input the symptoms, and the system predicts the disease which it thinks is the most likely cause.
Matching Symptoms: The application uses a trained Support Vector Classifier (SVC) model to classify the diseases.

Medical Recommendations:
Medications: Suggested medications for the diagnosed disease.
Precautions: Things to do in order to manage symptoms and prevent worsening.
Diet Plan: Recommended dietary modifications. 
Workout Plan: Exercises suitable to the disease.
User-Friendly Web Interface: Made from Flask and HTML templates.

Tech Stack
Backend: Flask (Python Web Framework)
Machine Learning: Support Vector Classifier (SVC) Model (pickle file)
Data Handling: Pandas & NumPy
Frontend: HTML, CSS (Jinja Templates)
Dataset: CSV files containing symptoms, diseases, medications, diet plans, and workouts

Installation & Setup
Prerequisites
Make sure Python 3.9+ is installed, along with the following libraries:
pip install flask pandas numpy scikit-learn
Clone the Repository
git clone https://github.com/yourusername/medical-recommendation-system.git
cd medical-recommendation-system

Run the Application
python main.py
The application should run on: http://127.0.0.1:5000/
