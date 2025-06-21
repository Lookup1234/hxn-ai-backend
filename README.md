# HXN AI Backend

This is the backend for the HXN Voice Assistant. It securely connects to OpenAI's GPT API to provide dynamic responses to voice input.

## How It Works

- Accepts POST requests at `/api/chat`
- Sends the input to OpenAI's Chat API (`gpt-3.5-turbo`)
- Returns the generated response

## Setup on Vercel

1. Clone or fork this repo
2. Add your OpenAI API key as an environment variable:
   - `OPENAI_API_KEY=your-key-here`
3. Deploy to Vercel
4. Your endpoint will be:
