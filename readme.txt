IPL Win Probability Predictor
This project is an IPL Win Probability Predictor developed using Machine Learning algorithms. It predicts the probability of a team winning a match based on input features like score, overs, wickets, etc.

Project Overview
This predictor uses two machine learning models:

Random Forest Classifier: Achieved an accuracy of 98%
Logistic Regression: Achieved an accuracy of 83%
The frontend is built using HTML, CSS, and JavaScript, and the application is hosted using Flask APIs.

Features
High Accuracy Prediction: The Random Forest model provides a high accuracy prediction (98%) based on the input data.
Interactive User Interface: The frontend is designed for an intuitive and seamless user experience.
API Integration: The predictor is hosted using Flask, enabling smooth interaction between the frontend and the backend.
Technologies Used
Machine Learning Models: Random Forest, Logistic Regression
Frontend: HTML, CSS, JavaScript
Backend: Flask, Python
Version Control: Git

How to Use

Clone the Repository:
git clone https://github.com/yourusername/ipl-win-probability-predictor.git
cd ipl-win-probability-predictor

Install the Required Packages:
pip install -r requirements.txt

Run the Application:
python app.py

Open in Browser:
Go to http://localhost:5000/ in your web browser.
Input Features: Enter the match data (runs, wickets, overs, etc.) and get the win probability prediction.

Project Structure
app.py: The Flask backend file.
models/: Contains the machine learning models and scripts.
static/: Contains the static files like CSS and JavaScript.
templates/: Contains the HTML templates.
requirements.txt: Lists the Python dependencies.

Future Enhancements
Add More Features: Incorporate more features like player form, match venue, etc.
Model Improvements: Experiment with other ML models to further improve accuracy.
Deployment: Deploy the application on a cloud platform.

