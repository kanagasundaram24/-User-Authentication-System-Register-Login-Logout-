# -User-Authentication-System-Register-Login-Logout-

This project is a simple user authentication system built using Flask and SQLite.
It allows users to register, login, access a protected dashboard, and logout securely.

Passwords are stored in hashed format using Werkzeug security.

🛠 Technologies Used

Python
Flask
SQLite
Werkzeug (Password Hashing)
HTML
CSS

Registration
User enters username and password
Password is hashed using generate_password_hash()
Data is stored in SQLite database
Redirects to Login page

Login
User enters username and password
Password is verified using check_password_hash()
If valid, session is created
User is redirected to Dashboard

Dashboard
Only accessible if user session exists
Displays logged-in username

Logout
Session is cleared
User is redirected to Login page

