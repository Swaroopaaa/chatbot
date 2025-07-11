PROJECT TITLE: Chatbot Application Using Python Flask & Gemini API

🔹 Overview
A simple yet intelligent chatbot built using Python Flask.

Provides real-time responses to user messages.

Integrates Google's Gemini API for enhanced conversation handling.

Maintains persistent chat history in a JSON file.

Includes the ability to clear chat history.

🔹 Features
Web-based interactive chat UI.

Dynamic responses using Gemini API.

Stores and displays previous conversations.

Option to clear chat history.

Easy-to-configure API key via .env file.

🔹 Technologies Used
Backend: Python, Flask

Frontend: HTML, CSS, JavaScript

Database: JSON file

API: Google Gemini API

Environment Management: python-dotenv

🔹 Setup Instructions
Make sure Python is installed on your machine.

Install required Python libraries:


pip install flask python-dotenv
Create a .env file in the root directory:


GOOGLE_API_KEY="your-api-key-here"
Run the Flask application:


python app.py
Open the browser and navigate to:


http://127.0.0.1:5000/
🔹 How to Obtain Gemini API Key
Visit: https://makersuite.google.com/app

Sign in with your Google account.

Go to: https://aistudio.google.com/app/apikey

Click "Create API Key".

Copy the key and paste it into your .env file as shown earlier.

🔹 Usage Guide
Type a message into the input field.

Click Send to receive a chatbot response.

Click Clear Chat to delete the conversation history.

🔹 Project Structure

chatbot_project/
│
├── app.py                → Flask backend logic
├── templates/
│   └── index.html        → Chat interface
├── static/
│   ├── style.css         → Chat UI styling
│   └── script.js         → Frontend JS logic
├── chat_history.json     → Stores chat history
├── .env                  → Gemini API key storage
└── README.md             → Project documentation
