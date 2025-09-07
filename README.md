# GenAI Chatbot for Research & Web Search

An interactive chatbot that leverages LangChain, Groq LLM, and multiple search tools to answer user queries with real-time web and research information. Built with Streamlit and deployed on Streamlit Cloud.

---

## Features

- Chat interface with conversation memory and live streaming responses.
- Integrated search tools:
  - DuckDuckGo – general web search
  - Arxiv – fetches top research papers
  - Wikipedia – retrieves top articles
- LangChain Zero-Shot React agent dynamically selects the right tool.
- Groq LLM (Llama3-8b-8192) provides natural language responses.
- Deployed on Streamlit Cloud for accessibility and scalability.

---

## Demo

Try the live app here: YOUR_STREAMLIT_APP_LINK

---

## Installation

1. Clone the repository:

git clone https://github.com/piyushugale/genai-chatbot.git
cd genai-chatbot

2. Create and activate a virtual environment (optional):

python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate

3. Install dependencies:

pip install -r requirements.txt

4. Add your Groq API Key in the Streamlit sidebar when running the app.

---

## Usage

Run the app locally:

streamlit run app.py

- Enter your Groq API Key in the sidebar.
- Type a question in the chat box.
- The agent will search the web or research sources and provide answers in real time.

---

## Technologies Used

Python, Streamlit, LangChain, Groq LLM, DuckDuckGo, Arxiv, Wikipedia APIs, Streamlit Cloud

---

## Skills

Python, Streamlit, LangChain, Groq LLM, API integration, Agent-based AI, Prompt engineering, Cloud deployment

---

## License

MIT License

---

## Author

Your Name – https://github.com/piyushugale