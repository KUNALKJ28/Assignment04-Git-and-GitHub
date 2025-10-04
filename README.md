# Assignment04-Git-and-GitHub
## To-Do List Flask Application
This project is a simple To-Do list application built with a Python Flask backend and a basic HTML frontend. It allows users to submit new to-do items, which are then stored in a MongoDB database.

## Features
Simple Web Form: A clean interface to add new to-do items.

Flask Backend: A lightweight backend to handle form submissions.

MongoDB Integration: Persistently stores to-do items in a MongoDB database, either locally or on MongoDB Atlas.

Environment-Based Configuration: Securely manages the database connection string using a .env file.

## How to Run the Project
Clone the Repository

Bash

git clone <your-ssh-repo-url>
cd <your-repo-name>
Install Dependencies
Make sure you have Python and pip installed.

Bash

pip install Flask pymongo python-dotenv
Set Up Environment Variables

Create a file named .env inside the flask_api_app/backend/ directory.

Add your MongoDB connection string to this file:

Code snippet

MONGO_URI="your_mongodb_connection_string"
Run the Server
Navigate to the backend directory and run the app.py file.

Bash

cd flask_api_app/backend
python app.py
Access the Application
Open your web browser and go to http://127.0.0.1:5000 to view the to-do list form.
