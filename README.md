# FitBuddy – AI Fitness & Nutrition Planner

FitBuddy is an AI-powered web application that generates personalized workout plans and nutrition tips using the **Google Gemini API**.

## 🚀 Features

* Personalized workout plans
* AI-generated nutrition tips
* Multiple fitness goals
* Workout intensity selection
* Feedback-based plan updates
* SQLite database
* FastAPI backend
* Simple web interface

## 🛠️ Technologies

* Python
* FastAPI
* HTML & CSS
* Jinja2
* SQLite
* SQLAlchemy
* Google Gemini API

## 📂 Project Structure

```text
FitBuddy/
├── app/
├── templates/
├── static/
├── tests/
├── .env
├── requirements.txt
└── README.md
```

## ⚙️ Setup

Create and activate the virtual environment:

```powershell
py -3 -m venv .venv
.venv\Scripts\activate
```

Install dependencies:

```powershell
python -m pip install -r requirements.txt
```

Add your Gemini API key to `.env`:

```env
GEMINI_API_KEY=YOUR_API_KEY
WORKOUT_MODEL=gemini-3.8-flash
NUTRITION_MODEL=gemini-3.8-flash
```

## ▶️ Run

```powershell
python -m uvicorn app.main:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

API documentation:

```text
http://127.0.0.1:8000/docs
```

## 🧪 Testing

```powershell
pytest -q
```

## ⚠️ Note

FitBuddy is an educational project. AI-generated fitness and nutrition recommendations should not replace professional medical or fitness advice.
