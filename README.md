# AI Email Generator API

This project is a FastAPI-based AI microservice that generates professional emails using OpenAI.

## Features

- FastAPI backend
- AI-generated email responses
- REST API endpoint
- Environment variable security
- Ready for deployment

## Tech Stack

- Python
- FastAPI
- OpenAI API
- Uvicorn
- python-dotenv

## Installation

Clone the repository:

git clone https://github.com/https://github.com/kiran-tariq/ai-email-generator-api.git

Go to project folder:

cd ai-email-generator-api

Create virtual environment:

python -m venv venv

Activate environment:

Windows:
venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

## Environment Variables

Create a `.env` file and add:

OPENAI_API_KEY=your_api_key_here

You can get an API key from OpenAI.

## Run the Server

uvicorn app:app --reload

Server will start at:

http://127.0.0.1:8000

## API Endpoint

POST /generate-email

Example Request:

{
 "topic": "product launch",
 "tone": "professional",
 "recipient": "marketing team"
}

Example Response:

{
 "generated_email": "Dear Marketing Team..."
}

## API Documentation

FastAPI automatically generates docs:

http://127.0.0.1:8000/docs

## Deployment

The API can be deployed using platforms like Render.

## Author
Kiran Tariq
