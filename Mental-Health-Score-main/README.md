# Mental Health Score Predictor
## About
Mental Health Score Predictor is a Python-based machine learning project that analyzes digital habits and lifestyle factors to predict a mental health score.

## Features
- Analyzes daily screen time and phone usage.
- Considers sleep, study hours and physical activity.
- Predicts a mental health score.
- Provides a simple web interface.

## Technologies Used
- Python
- FastAPI
- HTML
- CSS
- JavaScript
- Machine Learning

## Project Structure
- `main.py` – Backend application
- `index.html` – Webpage structure
- `style.css` – Page styling
- `script.js` – Frontend functionality
- `requirements.txt` – Required Python libraries
- `Mental_Health_Model.pkl` – Trained machine learning model

## How to Run

1. Install the required libraries:

   `pip install -r requirements.txt`

2. Start the backend:

   `python -m uvicorn main:app --reload --port 8000`

3. Open the API documentation:

   `http://127.0.0.1:8000/docs`

4. Open `index.html` using VS Code Live Server.

## Author
Daya Sravani

## Disclaimer
This project is developed for educational purposes only and is not a substitute for professional mental health assessment.
