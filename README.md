# ChatGPT Command-Line Chatbot

## Overview

This project is a command-line chatbot application built with Node.js that leverages OpenAI's GPT-3.5-turbo model for generating conversational responses. It allows users to interact with the chatbot in real-time, with the conversation context maintained through chat history.

## Features

- **Real-Time Interaction:** Engage in interactive conversations with the chatbot via the command line.
- **Contextual Responses:** Maintains conversation history to ensure relevant and coherent responses.
- **Error Handling:** Includes robust error handling to manage API issues and other exceptions.
- **Graceful Exit:** Type "exit" to end the chat session gracefully.

## Installation

Follow these steps to set up and run the chatbot:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/OKarpacz/ChatGPT-Chatbot-With-Node.js.git
   ```
   2. **Connect to catalog:**
   ```bash
   cd ChatGPT-Chatbot-With-Node.js
   ```
   1. **Install npm:**
   ```bash
   npm install
   ```
   1. **Enter your API key and save it as a .env file:**
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```
   1. **Start the app:**
   ```bash
   npm start
   ```
