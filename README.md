# AI-Agent

## Description
This AI Agent project allows users to interact with an AI through a web-based interface. 
It includes a frontend (`web-ui`) and backend (`src`) components and maintains chat history for user interactions.

This project was developed as part of the Labmentix Internship submission.

## Features
- Interactive AI Agent
- Web-based user interface
- Maintains conversation history
- Backend implemented in Python
- Easily deployable via Docker (optional)

## Project Structure
```text
AI-Agent-Labmentix/
│
├── web-ui/             # Frontend files (HTML, CSS, JS)
├── src/                # Backend scripts (Python)
├── tests/              # Test files
├── assets/             # Images or other assets
├── requirements.txt    # Python dependencies
├── Dockerfile          # Docker configuration
├── docker-compose.yml  # Docker Compose configuration
├── README.md           # Project description
└── other configuration files (.env, supervisord.conf, etc.)

1)How to Run

Clone the repository and navigate to the folder:

git clone https://github.com/yourusername/AI-Agent-Labmentix.git
cd AI-Agent-Labmentix

2)Install dependencies:

pip install -r requirements.txt

3)Run the backend server (if applicable):

python src/main.py

4)Open the web interface in a browser:

open web-ui/index.html

5)Run with Docker

If Docker is installed, you can start the project with:

docker-compose up


















