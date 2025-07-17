# Lung Cancer Prediction Web App

This is a Flask-based machine learning web app to predict the likelihood of lung cancer based on user inputs like smoking habits, chronic disease, and other health indicators.


## Features
- User-friendly web interface using Flask
- Email support via Flask-Mail
- Trained ML model (saved as `lc.model`)
- Real-time predictions
- Uses survey-based dataset

## Tech Stack

- Frontend: HTML (via Flask templates)
- Backend: Python, Flask
- ML Model: scikit-learn
- Database: SQLite (integrated)


##Screenshot
<img width="563" height="788" alt="image" src="https://github.com/user-attachments/assets/4014bfb5-1cb0-4ff4-8676-bf94f15961c8" />

## How to Run Locally

```bash
# Step 1: Create virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the Flask app
python app.py
