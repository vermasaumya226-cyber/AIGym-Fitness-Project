# AIGym-Fitness-Project
# AI Gym & Fitness Assistant

An AI-powered web application developed using **Python**, **Streamlit**, and **SQLite** to help users manage their fitness journey. The application provides BMI calculation, workout and diet recommendations, calorie estimation, water intake tracking, workout history, and an AI fitness chatbot.

---

## Features

- User Registration & Login
- User Profile Management
- BMI Calculator
- Personalized Workout Recommendation
- Diet Planner
- Water Intake Tracker
- Daily Calorie Calculator
- Dashboard
- Workout History
- AI Fitness Chatbot
- SQLite Database Integration

---

## Technologies Used

- Python
- Streamlit
- SQLite
- Pandas
- AI Chatbot
- VS Code

---

## Project Structure

```
AI_Gym_Fitness_Assistant/
│
├── app.py
├── gym.db
├── requirements.txt
│
├── database/
│   └── database.py
│
├── pages/
│   ├── Home.py
│   ├── Login.py
│   ├── Register.py
│   ├── BMI_Calculator.py
│   ├── Workout.py
│   ├── Diet.py
│   ├── Dashboard.py
│   ├── Water_Tracker.py
│   ├── Calorie_Calculator.py
│   ├── Workout_History.py
│   └── Chatbot.py
│
├── images/
│
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/vermasaumya226-cyber/AI_Gym_Fitness_Assistant.git
```

### 2. Open Project

```bash
cd AI_Gym_Fitness_Assistant
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

---

## Modules

### Login & Registration
Allows users to securely register and log in.

### BMI Calculator
Calculates Body Mass Index and classifies users into:
- Underweight
- Normal Weight
- Overweight
- Obese

### Workout Recommendation
Suggests workout plans based on BMI.

### Diet Planner
Provides personalized diet recommendations.

### Water Tracker
Tracks daily water intake.

### Calorie Calculator
Calculates estimated daily calorie requirements.

### Dashboard
Displays:
- Username
- BMI
- Water Intake
- Fitness Goal

### Workout History
Stores and displays previously saved workouts.

### AI Chatbot
Provides AI-powered fitness guidance.

---

## Database

### Users Table

| Column | Type |
|--------|------|
| id | INTEGER |
| name | TEXT |
| email | TEXT |
| password | TEXT |
| age | INTEGER |
| height | REAL |
| weight | REAL |

### Workout History Table

| Column | Type |
|--------|------|
| id | INTEGER |
| username | TEXT |
| workout | TEXT |
| date | TIMESTAMP |

---

## Future Enhancements

- AI Pose Detection using MediaPipe
- Workout Repetition Counter
- Progress Charts
- Cloud Database Integration
- Mobile Application
- Wearable Device Integration
- Admin Dashboard
- Advanced Analytics

---

## Learning Outcomes

This project demonstrates:

- Python Programming
- Streamlit Web Development
- SQLite Database Management
- AI Integration
- User Authentication
- Health & Fitness Recommendation System

---

## Developer

**Soumya Verma**

B.Tech (Artificial Intelligence & Machine Learning)
May Batch 2026

---

## License

This project is developed for educational purposes for major project.
