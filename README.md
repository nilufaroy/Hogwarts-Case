# Hogwarts Case Study AI Chat App

This is a simple AI chat web application built for the Private AI System case study.

The project allows a user to:
- enter a message
- submit it
- receive an AI-generated response

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Google Gemini API
- Google AI Studio
- python-dotenv

## Project Structure

```text
hogwarts-ai-chat/
│
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── templates/
    └── index.html
```

# How to Install Dependencies

## 1. Clone the repository
```bash
git clone https://github.com/yourusername/minimal-ai-chat-app.git
cd minimal-ai-chat-app
```

## 2. Create a virtual environment
python3 -m venv venv                

## 3. Activate the virtual environment
```bash
source venv/bin/activate            - it's for mac
```

## 4. Install required packages
pip install -r requirements.txt

# Environment Variables: 
## Create a .env file in the project folder and add your API key like this:
GROQ_API_KEY=your_api_key_here
 
# How to Run Locally:
## After installing dependencies and adding your API key, run:
python app.py

## Then open this in your browser:
http://127.0.0.1:5000

