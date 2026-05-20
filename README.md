# AI Onboarding Chatbot 🤖

An intelligent employee onboarding assistant powered by AI. 
New employees can ask questions about company policies and get 
personalized responses based on their role and background.

## What It Does
- Answers questions from company PDF documents
- Gives personalized responses based on employee profile
- Remembers conversation context
- Built with RAG (Retrieval Augmented Generation)

## Tech Stack
Python · LangChain · ChromaDB · Groq · LLaMA 3.1 · Streamlit

## How It Works
1. Company PDF documents are loaded into ChromaDB vector database
2. Employee profile (name, role, skills) is loaded
3. Employee asks a question
4. AI searches relevant documents and gives personalized answer

## How To Run

### 1. Clone the repo
git clone https://github.com/alomgirhm/ai-onboarding-chatbot

### 2. Install dependencies
pip install -r requirements.txt

### 3. Add API keys
Create a .env file:
GROQ_API_KEY=your_groq_api_key

### 4. Run the app
streamlit run app.py

## Use Cases
- Corporate employee onboarding
- HR policy question answering
- Company knowledge base assistant
- New hire training automation

## Project Structure
├── app.py           # Main application
├── assistant.py     # AI assistant logic
├── gui.py           # Streamlit interface
├── prompts.py       # AI prompt templates
├── requirements.txt # Dependencies
└── .env             # API keys (not uploaded)
