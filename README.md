# Gemini Q&A Web Application

A simple web application that uses Google's Gemini AI to answer questions.

## Features

- Clean and modern user interface
- Real-time answers from Google's Gemini AI
- Simple to use - just type your question and get an answer

## Prerequisites

- Node.js (version 14 or higher)
- A Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

## Setup and Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Install dependencies:
   ```
   npm install
   ```
4. Create a `.env` file based on the `.env.example` file:
   ```
   cp .env.example .env
   ```
5. Edit the `.env` file and add your Gemini API key
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

## Running the Application

1. Start the server:
   ```
   npm start
   ```
   Or for development with auto-restart:
   ```
   npm run dev
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## How to Use

1. Type your question in the text area
2. Click "Ask Gemini" or press Enter
3. Wait for Gemini to process and display the answer

## Notes

- This application requires an internet connection to communicate with the Gemini API
- API usage may be subject to limits based on your API key's quota

## License

This project is open source and available for personal and commercial use. 

## ngrok

To use ngrok for temporary hosting, follow these steps:

1. Install ngrok from [ngrok.com](https://ngrok.com)
2. Run the following command to create a tunnel:
   ```
   ngrok http 3000
   ```

This will provide you with a public URL that you can use to access your application from anywhere. 