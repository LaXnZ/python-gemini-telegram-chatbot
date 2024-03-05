# Gemini Telegram Chatbot

This repository contains a Python Telegram chatbot integrated with the Gemini conversational AI model from Google. With this bot, you can have engaging conversations with users on Telegram using advanced AI capabilities.

## Installation

1. Install the required Python packages:

   - [telebot](https://pypi.org/project/telebot/): A library for interacting with the Telegram Bot API.
     ```bash
     pip install telebot
     ```

   - [google-generativeai](https://github.com/google/generative-ai-python): A Python client library for accessing Google's generative AI models, including Gemini.
     ```bash
     pip install google-generativeai
     ```

   - [python-dotenv](https://pypi.org/project/python-dotenv/): A library for managing environment variables from a .env file.
     ```bash
     pip install python-dotenv
     ```

2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/LaXnZ/python-gemini-telegram-chatbot.git
   ```

3. Navigate to the project directory:
   ```bash
   cd python-gemini-telegram-chatbot
   ```

4. Create a `.env` file in the project directory and add your Telegram bot token and Gemini API key:
   ```plaintext
   TELEGRAM_TOKEN=your_telegram_token_here
   GENAI_API_KEY=your_genai_api_key_here
   ```

## Usage

1. Run the bot script using Python:
   ```bash
   python main.py
   ```

2. Start a conversation with your bot on Telegram and enjoy interactive conversations with the Gemini AI model.

## Contributing

Contributions to this project are welcome! If you have any ideas for improvements or new features, feel free to fork the repository, make your changes, and submit a pull request.

---

Replace `your_telegram_token_here` and `your_genai_api_key_here` in the `.env` file with your actual Telegram bot token and Gemini API key. Customize the instructions and placeholders as needed for your specific project.
