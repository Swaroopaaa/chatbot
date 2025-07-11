CHATBOT APPLICATION USING PYTHON FLASK AND GEMINI API

OVERVIEW
This is a lightweight, intelligent chatbot built using Python Flask. It interacts with users via a web interface and can respond intelligently based on predefined logic. It also integrates Google's Gemini API for advanced responses. Chat history is maintained in a JSON file, and users can clear previous chats at any time.

FEATURES

User-friendly web interface

Real-time chatbot interaction

Integration with Gemini API (.env based)

Persistent chat history using JSON

Clear Chat functionality

TECHNOLOGIES USED

Backend: Python, Flask

Frontend: HTML, CSS, JavaScript

Data Storage: JSON

API: Google Gemini

Environment: python-dotenv

SETUP INSTRUCTIONS

Ensure Python is installed on your system.

Install the required packages:


pip install flask python-dotenv
Create a .env file and add your Gemini API key:


GOOGLE_API_KEY="your-api-key-here"
Run the application:


python app.py
Open your browser and go to:
http://127.0.0.1:5000/

HOW TO GET GEMINI API KEY

Go to: https://makersuite.google.com/app

Sign in with your Google account

Navigate to: https://aistudio.google.com/app/apikey

Click on Create API Key

Copy the key and paste it in your .env file as shown above

HOW TO USE

Type your message and click Send

The chatbot responds instantly

Click Clear Chat to delete previous messages

PROJECT STRUCTURE

chatbot_project/
│
├── app.py                → Flask backend
├── templates/
│   └── index.html        → Chat UI
├── static/
│   ├── style.css         → CSS styling
│   └── script.js         → Frontend JavaScript
├── chat_history.json     → Stores chat logs
├── .env                  → API Key storage
└── README.md             → Documentation
