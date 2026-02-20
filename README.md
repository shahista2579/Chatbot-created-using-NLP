📌 Overview

This project implements an intelligent chatbot using Natural Language Processing (NLP) techniques. The chatbot understands user intents and provides appropriate responses based on predefined patterns stored in an intents dataset.

It leverages:

NLTK for text preprocessing

Scikit-learn for machine learning–based intent classification

Streamlit for building an interactive web interface

The chatbot is designed as an academic project demonstrating NLP, text classification, and real-time user interaction.

🚀 Features

Recognizes user intents such as greetings, farewells, gratitude, etc.

Provides relevant responses based on trained machine learning model

Maintains conversation history

Easy to extend with new intents

Interactive and user-friendly web interface

🛠️ Technologies Used

Python

NLTK

Scikit-learn

Streamlit

JSON (for intents dataset)

CSV (for chat history logging)

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/shahista2579/Chatbot-created-using-NLP.git
cd Chatbot-created-using-NLP
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate   # On Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Download Required NLTK Data
import nltk
nltk.download('punkt')
▶️ Usage

Run the application using:

streamlit run app.py

After running, the chatbot will open in your browser.
Type your message in the input box and interact with the chatbot in real time.

📂 Intents Data

The chatbot behavior is defined in intents.json, which contains:

Tags

Patterns

Responses

You can modify this file to:

Add new intents

Update responses

Expand chatbot knowledge

📝 Conversation History

All conversations are stored in:

chat_log.csv

You can view previous interactions through the sidebar option in the application.

🤝 Contributing

Contributions are welcome!
Feel free to:

Open issues

Suggest improvements

Submit pull requests

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgments

NLTK for NLP preprocessing

Scikit-learn for machine learning algorithms

Streamlit for building the interactive interface
