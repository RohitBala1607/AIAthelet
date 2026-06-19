# AIAthelet

AIAthelet is a Python-based AI assistant built using Groq, LangChain, and LangGraph. It includes both a conversational chatbot and a tool-enabled agent capable of executing Python code and retrieving real-time information from the web.

## Features

* Conversational AI powered by Groq
* ReAct agent architecture
* Python code execution support
* Web search capabilities
* Context-aware responses
* Interactive command-line interface

## Models

* Llama 3.3 70B Versatile

## Technologies Used

* Python
* Groq API
* LangChain
* LangGraph
* PythonREPL
* Requests
* Serper Search API

## Components

### AI Chatbot

A conversational assistant that maintains chat history and provides context-aware responses.

### AI Agent

A tool-enabled agent with support for:

* Python code execution
* Real-time web search
* Dynamic reasoning using ReAct

## Installation

Clone the repository:

```bash
git clone https://github.com/RohitBala1607/AIAthelet.git
cd AIAthelet
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

Windows:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure environment variables:

```env
GROQ_API_KEY=your_groq_api_key
SERPER_API_KEY=your_serper_api_key
```

Run the chatbot:

```bash
python "Ai assit"
```

Run the AI agent:

```bash
python "Ai assit2"
```

## Project Structure

```text
AIAthelet/
├── Ai assit
├── Ai assit2
├── requirements.txt
├── README.md
└── .env
```

## Future Enhancements

* Memory support
* RAG integration
* Voice interaction
* GUI and web interface
* Multi-agent architecture

## Author

Rohit Bala

GitHub: https://github.com/RohitBala1607
