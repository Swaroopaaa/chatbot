Chatbot Application using Python Flask and Gemini API

Overview
This project is a lightweight, intelligent chatbot developed using Python Flask. It responds to user inputs using predefined logic and integrates with Google's Gemini API for more dynamic responses. The application features a web-based interface with persistent chat history stored in JSON format. Users also have the option to clear chat history for privacy or reset purposes.

Features

Simple and intuitive web UI

Real-time chatbot interaction

Integration with Gemini API using .env configuration

Chat history saved in chat_history.json

Option to clear previous chats

Technologies Used

Backend: Python, Flask

Frontend: HTML, CSS, JavaScript

Storage: JSON file for chat logs

API Integration: Google Gemini via API Key

Environment Management: python-dotenv

Setup Instructions

Ensure Python and pip are installed in your environment.

Install dependencies:


pip install flask python-dotenv
Add your Gemini API key in a .env file:


GOOGLE_API_KEY="your-api-key-here"
Start the application:


python app.py
Open a browser and navigate to:
http://127.0.0.1:5000/

How to Obtain and Configure Google Gemni API Key
Go to https://makersuite.google.com/app and sign in with your Google account.

Accept the terms and start using the platform.

Visit https://aistudio.google.com/app/apikey.

Click on "Create API Key" to generate your Gemini API key.

Copy the key and use it in your project as needed.

Usage Instructions

Enter a message in the text box and click Send

The chatbot will respond accordingly

Use the Clear Chat button to remove previous conversations from the interface and chat_history.json

Project Structure


chatbot_project/
│
├── app.py                → Flask backend logic
├── templates/
│   └── index.html        → Chat UI template
├── static/
│   ├── style.css         → Frontend styles
│   └── script.js         → Handles frontend interactions
├── chat_history.json     → Stores persistent chat logs
├── .env                  → Contains the Gemini API Key
└── README.md             → Project documentation
