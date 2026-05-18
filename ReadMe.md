# 🏋️‍♀️ R.I.S.E. Fitness

R.I.S.E. Fitness is a full-stack Flask web application that helps users track meals, workouts, and progress through a personalized dashboard.  
It was built as part of my full-stack training to practice authentication, database integration, REST-style routing, and dynamic UI rendering with Flask and MySQL.

## 💡 What This Project Does

This is a personal health and fitness web application where users can:

- Log in securely with an email and password
- Upload their details and fitness goals
- Select and read articles from the Wellness Blog
- Watch workouts tailored to their fitness goals and mark them as completed
- Log their desired Meal Plan for the week
- View a dashboard with:
  - 🥗 Their saved Meal plan for the week
  - 🏋️ Custom Workout plans 
  - 📈 Weekly progress tracking (workouts done)
  - 📰 Blog articles or helpful tips

It’s designed to motivate users and help them track their health journey—all in one place.

## 🎯 Purpose of the Project

This project was built to practice and showcase full-stack development skills, particularly:

- Building a multi-page Flask web app
- Using MySQL as a relational database
- Organizing code into routes, data_access, and templates
- Applying Jinja2 for dynamic rendering
- Designing a user-friendly interface with Bootstrap and custom CSS

## 🧠 Why This Project is Useful
- Combines fitness, nutrition, and self-improvement in a single dashboard
- Encourages users to stay on track with their health goals
- Demonstrates how to build a full-featured web app using Flask, with real-world features like authentication, database integration, and clean UI components

## 🧱 Main Features

| Feature                    | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🔐 **User Login**          | Users can securely log in and access their dashboard                        |
| 📊 **Dashboard**           | Central hub with all personal content                                       |
| 📖 **Blog/Articles**       | Helpful fitness and nutrition-related content                               |
| 🥦 **Daily meals dashboard**           | Gives opportunity to log their weekly meal plan to inspire healthy eating   |
| 🏃 **Workout recommendations**       | Daily or weekly routines for different fitness levels and goals             |


## 🛠️ Technologies Used

- Python 3.12
- Flask
- Jinja2 Templates
- MySQL
- HTML/CSS (Bootstrap)
- JavaScript

## Team contributions

# Ivon Martinez Genis:
My main contributions to this project included:
- building Flask routes and backend logic
- implementing user authentication and session-based login flows
- working with MySQL data models and database queries
- creating and styling user-facing pages
- testing routes and app functionality during team development

## 🛠️ Installation & Local Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   git clone https://github.com/Ivon-Martinez/RISE-Fitness.git
   cd RISE-Fitness

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

4. Database Setup:
Ensure you have MySQL installed and running.
Create a database for the project and update the configuration in the app.

5. Run the application:
python app.py
