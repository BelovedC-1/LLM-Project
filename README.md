# LLM Q&A System with Gemini API

## Project Overview
This is a Question & Answering system that uses Google's Gemini API. It includes both a Command-Line Interface (CLI) and a Web GUI built with Flask.

## Features
- Python CLI application (`LLM_QA_CLI.py`)
- Flask Web GUI (`app.py`) 
- Natural language preprocessing (tokenization, lowercasing, punctuation removal)
- Integration with Google Gemini AI model
- Graceful error handling with fallback responses

## Setup Instructions

### Prerequisites
- Python 3.9+
- Google Gemini API key

### Installation
1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Set your Gemini API key:
```bash
export GEMINI_API_KEY="your_api_key_here"
```

### Usage

#### Command Line Interface
```bash
python LLM_QA_CLI.py "Your question here"
```
or run without arguments to be prompted:
```bash
python LLM_QA_CLI.py
```

#### Web Interface
1. Start the Flask app:
```bash
python app.py
```

2. Open your browser to: `http://127.0.0.1:5000`

3. Enter your question and click "Ask LLM"

## Project Structure
```
LLM_QA_Project_placeholder/
├── LLM_QA_CLI.py              # Command-line interface
├── app.py                     # Flask web application
├── requirements.txt           # Python dependencies
├── templates/
│   └── index.html            # Web interface template
├── LLM_QA_hosted_webGUI_link.txt  # Deployment info
└── README.md                 # This file
```

## Features Implemented
- ✅ Natural language preprocessing
- ✅ Gemini API integration
- ✅ CLI interface with argument support
- ✅ Modern web GUI with Flask
- ✅ Error handling and fallback responses
- ✅ Question preprocessing display
- ✅ Clean, user-friendly interface

## API Information
- Uses Google Gemini 2.0 Flash model
- Free tier available
- No credit card required for basic usage
