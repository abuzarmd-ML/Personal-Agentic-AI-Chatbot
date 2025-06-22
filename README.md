# Personal-Agentic-AI-Chatbot

This project is perfect for developers (like myself) who are exploring agentic AI architectures and want to learn how to:

- Integrate LLMs using modern frameworks like LangGraph and LangChain

- Build and deploy interactive, production-ready GenAI applications

- Create a seamless experience across FastAPI (backend) and Streamlit (frontend)

# TECHNICAL ARCHITECTURE
![chatbot workflow drawio](https://github.com/user-attachments/assets/42d74f00-fc6f-4a5f-a10c-8787d5ba228b)

# PROJECT LAYOUT
Phase1–Create AI Agent
1. Setup API Keys for Groq and Tavily
2. Setup LLM & Tools
3. Setup AI Agent with Search tool functionality
   
Phase2–Setup Backend (With FastAPI)
1. Setup Pydantic Model (Schema Validation)
2. Setup AI Agent from FrontEnd Request
3. Run app & Explore Swagger UI Docs

Phase3–Setup Frontend
1. Setup UI with streamlit (model provider, model, system prompt, query)
2. Connect with backend via URL

# TOOLS AND TECHNOLOGIES
- LangGraph ReAct Agents
- FastAPI for API calls
- Groq & OpenAI for LLM
- Streamlit for UI (Frontend)
- Langchain for tools
- Uvicorn for hosting the App
- Python
- VS Code

# Setting Up a Python Virtual Environment
## Using Pipenv
- Install Pipenv (if not already installed):
  
    `pip install pipenv`

- Install Dependencies with Pipenv:
  
    `pipenv install`
- Activate the Virtual Environment:
  
    `pipenv shell`

## Using pip and venv
- Create a Virtual Environment:
  
    `python -m venv venv`

- Activate the Virtual Environment:
  
macOS/Linux:

    source venv/bin/activate
  
Windows:

    venv\Scripts\activate

## Install Dependencies:
    pip install -r requirements.txt

# Project Phases and Python Commands

## Phase 1: Create AI Agent
    
    python ai_agent.py

## Phase 2: Setup Backend with FastAPI

    python backend.py
## Phase 3: Setup Frontend with Streamlit

    python frontend.py
