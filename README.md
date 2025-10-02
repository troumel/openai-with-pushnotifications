# My AI Assistant

A personal AI assistant application built with OpenAI's API and Gradio.

## Features

- Interactive chat interface using Gradio
- PDF document reading and analysis
- Push notifications via Pushover
- Tool calling capabilities for personalized responses
- Includes personal CV and summary for enhanced AI assistant personalization

## Setup

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your API keys:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   PUSHOVER_USER=your_pushover_user_key_here
   PUSHOVER_TOKEN=your_pushover_app_token_here
   ```
4. Run the application:
   ```
   python app.py
   ```

## Usage

The application will start a web interface where you can chat with your AI assistant. The assistant can read PDF files and send push notifications when needed.

The assistant has access to:
- `summary.txt` - Personal information and background
- `Roumeliotis_Theodoros_CV.pdf` - Professional CV for career-related questions

## Deployment

This application is designed to work with HuggingFace Spaces for easy deployment.