# OpenAI-Powered Chatbot with Image Generation and Memory

## Overview

This project demonstrates the use of the OpenAI API to create a versatile chatbot capable of generating text responses, creating images, generating image variations, and remembering past conversations. It leverages the `.env` file for secure API key management and implements a conversational memory feature to enhance user experience.

## Features

-   **Chatbot**: Generates dynamic text responses using OpenAI's language models.
-   **Image Generation**: Creates images based on text prompts using OpenAI's DALL-E.
-   **Image Variations**: Generates variations of uploaded images.
-   **Conversation History**: Remembers past conversations to provide contextually relevant responses.
-   **Secure API Key Management**: Uses `.env` file to securely store and access the OpenAI API key.

## Technologies Used

-   Python
-   OpenAI API
-   `dotenv` library

## Prerequisites

-   Python 3.6+
-   OpenAI API key (You can obtain one [here](https://platform.openai.com/account/api-keys))

## Setup

1.  **Clone the repository:**    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Install the required Python packages:**
    ```bash
    pip install openai python-dotenv
    #If you have a web interface add other libraries here:
    #pip install flask
    ```

3.  **Create a `.env` file:**

    In the root directory of the project, create a `.env` file and add your OpenAI API key:

    ```
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY
    ```
    **Note**: Replace `YOUR_OPENAI_API_KEY` with your actual API key.


## Usage

### Text Generation (Chatbot)

1.  Run the code.
2.  Enter your message/prompt when prompted.
3.  The chatbot will generate a response based on your input.

### Image Generation

1.  Use the appropriate command/input to trigger image generation.
2.  Provide a text prompt for the image you want to create.
3.  The application will use DALL-E to generate an image based on your prompt and display or save it.

### Image Variations

1.  Upload an image to the application (if applicable).
2.  Use the appropriate command/input to generate image variations.
3.  The application will generate variations of the uploaded image and display or save them.

### Conversation History

-   The chatbot remembers past conversations within a session.
-   You can continue the conversation by providing follow-up prompts, and the chatbot will consider the previous context.


# Author
Aliraza Amjad Shaikh

https://www.linkedin.com/in/aliraza-shaikh-146b22357/
