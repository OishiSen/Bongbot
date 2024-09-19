# Bongbot
A bilingual Bengali-English chatbot using Groq API and Deep Translator. The bot processes Bengali input, translates it to English, generates a response using the Llama3-8B model, and translates the output back to Bengali.

# Bengali-English Bilingual Chatbot using Groq API

This project is a command-line chatbot that processes Bengali input, translates it to English for response generation using the Groq API, and translates the output back to Bengali. The bot leverages the Llama3-8B model for generating natural responses.

## Features

- **Bengali-English Translation**: Seamlessly handles translation from Bengali to English and vice versa.
- **Groq AI Integration**: Uses Groq’s Llama3-8B model for generating high-quality responses.
- **Simple CLI Interface**: Chat in Bengali using a user-friendly command-line interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```

2. Install dependencies:
    ```bash
    pip install groq deep-translator
    ```

## Usage

1. Replace the API key in the script with your own:
    ```python
    api_key = 'your_api_key_here'
    ```

2. Run the chatbot:
    ```bash
    python chatbot.py
    ```

3. Start chatting in Bengali! Type "exit" to end the conversation.

## Code Overview

- **query_groq()**: Sends translated input to the Groq model and retrieves a response.
- **chatbot()**: Handles the chat loop, translating inputs and outputs as needed.

## Future Enhancements

- Add a graphical interface (GUI).
- Expand support for other languages.
- Improve contextual understanding for smoother conversations.

## License

This project is licensed under the MIT License.
