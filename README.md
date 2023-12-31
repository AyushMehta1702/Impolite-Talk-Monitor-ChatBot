# Impolite Talk Monitor ChatBot
 Impolite Talk Monitor ChatBot - OpenAI LLM

## Description

Welcome to the Impolite Talk Monitor Chatbot repository! This project features a chatbot named "Ayurvi" that monitors user input for impolite behavior and responds accordingly. It is powered by OpenAI's GPT-4.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Configuration](#configuration)
- [Tests and Results](#tests-and-results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Impolite Talk Monitoring:** The chatbot actively monitors user input for impolite behavior.
- **Polite Responses:** Responds politely to user input, but exits if impolite behavior is detected.

## Getting Started

### Prerequisites

- Python 3.x
- [OpenAI API Key](https://beta.openai.com/signup/)
- [dotenv](https://pypi.org/project/python-dotenv/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AyushMehta1702/impolite-talk-monitor-chatbot.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the project root and add your OpenAI API key:

    ```env
    OPENAI_API_KEY=your-api-key-goes-here
    ```

### Usage

1. Run the chatbot:

    ```bash
    python ayurvi_chatbot.py
    ```

2. Start chatting with Ayurvi. Type "exit" or "quit" to end the conversation.

## Configuration

- **Model Selection:** Customize the model used by modifying the `model` parameter in the `ChatCompletion.create` method in `chatbot.py`.
- **Response Settings:** Adjust the `temperature` and `max_tokens` parameters in the `ChatCompletion.create` method to control the response generation.

## Tests and Results
[Talk Results](test_and_resulting_talk.png)

## Contributing
Feel free to contribute to the project by submitting issues or pull requests.

## Acknowledgments
Thanks to OpenAI for providing the GPT-4 model.
