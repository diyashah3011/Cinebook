CineBook 🎟️
A full-stack event booking application built with Python, MySQL, and Streamlit that allows users to book tickets for Movies, Comedy Shows, and Concerts with an interactive seat selection system.
Features

🎬 Browse & book Movies, Comedy Shows, and Concerts
💺 Row-wise interactive seat selection with dynamic pricing (Economy → Premium)
💳 Simulated payment gateway with booking confirmation
🔐 User registration & OTP-based login authentication
📊 Admin dashboard with sales & revenue analytics (Plotly charts)
📁 Booking history management

Tech Stack

Frontend: Streamlit
Backend: Python
Database: MySQL
Libraries: Pandas, Plotly, NumPy

Python Concepts Used

OOP with Abstract Base Classes
Custom Exception Handling (BookingException, PaymentException)
Dataclasses for seat info
File Operations
NumPy for data processing

Setup

Clone the repo
Install dependencies: pip install streamlit mysql-connector-python pandas plotly numpy
Import cinebook8.sql into your MySQL database
Run: streamlit run cinebook.py
