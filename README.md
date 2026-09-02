# Gemini AI Text Generator 🤖

An AI-powered text generation web application built using the **Google Gemini API** and **Gradio**.

The application provides a simple web interface where users can enter a prompt and receive an AI-generated text response using Google's Gemini generative AI model.

## 🚀 Features

- Generate AI-powered text from user prompts
- Simple and interactive Gradio interface
- Powered by Google Gemini API
- Real-time response generation
- Easy to run locally
- Beginner-friendly Generative AI project

## 🛠️ Technologies Used

- Python
- Google GenAI SDK
- Google Gemini API
- Gradio
- Jupyter Notebook

## 📂 Project Structure

```text
Gemini-AI-Text-Generator/
│
├── 1st test.ipynb
├── README.md
├── requirements.txt
└── .gitignore

⚙️ Installation
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Gemini-AI-Text-Generator.git
cd Gemini-AI-Text-Generator
2. Install dependencies
pip install -r requirements.txt

Or install them manually:

pip install -U google-genai gradio
🔑 API Key Setup

This project requires a Google Gemini API key.

Never hard-code your API key directly into the source code.

Set your API key as an environment variable.

Linux / macOS
export GEMINI_API_KEY="your_api_key_here"
Windows
set GEMINI_API_KEY=your_api_key_here

Then access it in Python:

import os
from google import genai

api_key = os.getenv("GEMINI_API_KEY")

client = genai.Client(api_key=api_key)
▶️ Running the Application

Run the Python/Gradio application:

python app.py

Gradio will start a local web server.

Open the displayed local URL in your browser.

💡 How It Works

The application follows a simple workflow:

User enters prompt
        ↓
Gradio Interface
        ↓
Google Gemini API
        ↓
Gemini generates response
        ↓
Generated text displayed to user
🖥️ User Interface

The application contains:

Prompt Input – Enter the question or instruction.
Submit Button – Sends the prompt to Gemini.
Generated Text – Displays the AI-generated response.
Clear Button – Clears the input and output fields.
🧪 Example
Input
What is Machine Learning? Explain it to a school student.
Output
Machine Learning is a technology that allows computers
to learn from data and make decisions without being
explicitly programmed for every task...
📌 Example Prompts

You can try prompts such as:

Explain Artificial Intelligence in simple words.
Write a Python program to check whether a number is prime.
Explain Cloud Computing to a beginner.
What is Model Context Protocol?
Write a short story about an AI robot.
🔐 Security

Do not commit API keys, passwords, or other secrets to GitHub.

Use environment variables for sensitive credentials.

Add the following to .gitignore:

.env
*.env
__pycache__/
.ipynb_checkpoints/
🔮 Future Improvements

Possible improvements for this project include:

Add chat history
Add multiple Gemini model options
Add temperature and generation settings
Add streaming responses
Add Markdown output
Add conversation memory
Add file upload support
Deploy the application online
Improve UI/UX
Add authentication
📚 Learning Outcomes

Through this project, you can learn:

How to use the Google GenAI SDK
How to interact with Gemini models using an API
How to build a simple Generative AI application
How to create web interfaces using Gradio
How to handle API credentials securely
How to integrate AI models into Python applications
👨‍💻 Author

Shivam Gaike

B.Tech – Artificial Intelligence & Data Science

⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
