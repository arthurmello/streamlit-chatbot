# Streamlit Chatbot

This is a simple chatbot application built using Streamlit and OpenAI's GPT-3.5-turbo model. The application allows users to interact with an AI assistant through a web interface.

## Features

- Interactive chat interface
- Utilizes OpenAI's GPT-3.5-turbo for generating responses
- Maintains chat history during the session

## Requirements

- Python 3.7 or higher
- Streamlit
- OpenAI Python client

## Setup

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd streamlit-chatbot
   ```

2. **Install Poetry (if you haven't already):**

   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```

3. **Install dependencies:**

   ```bash
   poetry install
   ```

3. **Set up your OpenAI API key:**

   Ensure your `streamlit secrets` are configured with your OpenAI API key. You can do this by creating a `.streamlit/secrets.toml` file:

   ```toml
   [secrets]
   OPENAI_API_KEY = "your-openai-api-key"
   ```

4. **Run the application:**

   ```bash
   poetry run streamlit run app.py
   ```

## Usage

- Open your web browser and go to `http://localhost:8501` to interact with the chatbot.
- Type your message in the input box and press enter to receive a response from the AI assistant.