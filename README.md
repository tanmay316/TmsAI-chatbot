TmsAI Chatbot with Langchain, Ollama and OpenAI API

This repository contains code for building a conversational AI chatbot named TmsAI using Langchain, ollama and the OpenAI API. TmsAI is designed to provide helpful responses to user queries on various topics.

Setup
To run the TmsAI chatbot, follow these steps:

Clone this repository to your local machine:

git clone gh repo clone tanmay316/TmsAI-chatbot

Install the required Python packages listed in the requirements.txt file:
pip install -r requirements.txt

Create a .env file in the root directory of the project and add your API keys:
LANGCHAIN_API_KEY=your_langchain_api_key
OPENAI_API_KEY=your_openai_api_key

Usage
To use the TmsAI chatbot, run the Streamlit app:

streamlit run app.py

This will start a local server, and you can access the chatbot interface in your web browser.

Features
Langchain Integration: Utilizes Langchain for natural language processing and conversation flow management.
OpenAI API: Integrates the OpenAI API for generating responses to user queries.
Streamlit Interface: Provides a user-friendly interface for interacting with the chatbot.

File Structure
app.py: Main file containing the Streamlit app setup and UI components.
locallama.py:  Main file containing the Streamlit app setup and UI components.
README.md: Documentation file providing information about the project.
requirements.txt: Text file listing the Python dependencies required for the project.
.env: Configuration file for storing API keys securely.

Contributing
Contributions to this project are welcome! If you have any suggestions, bug fixes, or feature implementations, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Created by Your Tanmay Sharma
