🏆 House Points System (Python + guizero)

A House Points System developed for my BTEC Level 3 IT Unit 4 Programming Project.
This application allows teachers to log in, manage student records, award house points, and view an automatically updating leaderboard. The system was built in Python using the guizero library for the graphical user interface and JSON files for storage.

🚀 Features

👩‍🏫 Teacher Login System (username + password check)

➕ Add New Students (saved to JSON)

➖ Remove Students

🎯 Award or Deduct House Points

🥇 Live Leaderboard sorted by highest points

💾 Persistent Storage using JSON files

🖥️ Simple GUI built with guizero

🧪 Validation & error messages for user mistakes

🛠️ Technologies Used

Python 3

guizero (GUI library)

JSON (file-based data storage)

Built-in modules: json, os

📂 File Structure
📂 Guizero 
housepoints.py          → Main application
students.json           → Student data storage
teachers.json           → Teacher login storage
readmeAlternative.txt   → Original starter notes from teacher

📘 How It Works

Teacher logs in using credentials from teachers.json.

Main menu appears with options:

Add student

Award points

View leaderboard

JSON files update automatically whenever data changes.

Leaderboard sorts students by highest points.

🧪 Testing & Reliability

The system was tested using:

Correct & incorrect login attempts

Adding students with valid/invalid input

Awarding points and updating the leaderboard

Navigating between screens

Small bugs may still exist because the project was created in Year 12, but the main functionality works reliably.

🔧 Limitations

No student login feature

No password hashing (simple JSON storage)

Adding students does not fully prevent empty fields (future improvement)

GUI layout may vary slightly on different screen sizes

🎯 What I Learned

This project helped build skills in:

Python programming

GUI design with guizero

JSON data handling

SDLC planning & documentation

Testing & debugging

User-focused design

📅 Project Status

✔ Completed – Submitted for Unit 4BC (Programming)
Minor improvements planned for a later version.
