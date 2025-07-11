
Chatbot Application Using Python Flask & Gemini API



1. Project Overview

      1. This is a web-based chatbot developed using Python Flask.


      2. It uses the Google Gemini API to generate intelligent responses.


      3. Chat history is saved in a local JSON file.


      4. Users can delete past chats using the Clear Chat button.


      5. Lightweight and user-friendly interface with HTML, CSS, and JavaScript.



2. Features

    1. Interactive chat interface with real-time responses.


    2. Stores conversation history locally.


    3. Clean UI with Send and Clear buttons.


    4. Gemini API integration for AI-powered replies.


    5. Easy-to-modify and extend for advanced use cases.



3. Technologies Used

     1. Languages: Python, HTML, CSS, JavaScript


     2. Backend: Flask


     3. Frontend: HTML/CSS + script.js


     4. API: Google Gemini


     5. Storage: JSON file (chat_history.json)


     6. Environment Management: python-dotenv


4. Setup Instructions

      1. Ensure Python 3.x is installed.


      2. Install required packages:

           pip install flask python-dotenv


      3. Create a .env file and paste your Gemini API key:

          GOOGLE_API_KEY="your-api-key-here"


      4. Start the application:

         python app.py


      5. Open your browser and go to:

          http://127.0.0.1:5000/




5. How to Get Gemini API Key

      1. Visit https://makersuite.google.com/app


      2. Sign in using your Google account.


      3. Go to https://aistudio.google.com/app/apikey


      4. Click “Create API Key”.


      5. Copy the key and paste it into .env file as shown above.

6. How to Use the Chatbot

      1. Type your message in the input field.


      2. Click the Send button to receive a response.


      3. Click the Clear Chat button to delete all previous messages.



7. Project Structure

      chatbot_project/
      │
      ├── app.py                → Flask backend
      ├── templates/
      │   └── index.html        → Chat UI
      ├── static/
      │   ├── style.css         → Page styling
      │   └── script.js         → Button and input logic
      ├── chat_history.json     → Stores user chats
      ├── .env                  → Contains Gemini API Key
      └── README.md             → Project documentation



