# 🤖 Q&A Chatbot with Ollama, LangChain & Streamlit

This project is a simple yet powerful **Q&A chatbot** built using **open-source LLMs** through [Ollama](https://ollama.com), powered by **LangChain** and served through a clean **Streamlit** interface.

It allows users to ask questions and get meaningful responses — including programming help, AI concepts, and general knowledge — all using **local models** (like `mistral`) without relying on OpenAI or external APIs.


## 💡 Features

- 🔓 **Local LLM Support** via Ollama (e.g., Mistral)
- 🧱 LangChain-powered Prompt Chaining
- 🎛️ Adjustable Temperature & Token Limits
- 🎨 Sleek UI via Streamlit
- 📦 `.env` integration for secure key management
- 🧠 LangSmith tracking enabled

---

## 🚀 Tech Stack

| Tool       | Usage |
|------------|-------|
| `LangChain` | Prompt templates, chaining, integration |
| `Ollama`    | Running open-source LLMs locally |
| `Streamlit` | UI for chatbot interaction |
| `dotenv`    | Environment variable management |
| `Python`    | Core backend logic |
| `LangSmith` | Trace logging & analysis |

---
## ⚙️ Setup Instructions

### 1. Clone the Repository
  git clone https://github.com/yourusername/qna-chatbot-ollama.git
  cd qna-chatbot-ollama

### 2. Create a Virtual Environment (Python 3.10)
# On Windows:
  conda create -p venv python==3.10
# On macOS/Linux:
  source venv/bin/activate
### 3. Install required packages
  pip install -r requirements.txt

### Create a .env file in root:
  LANGCHAIN_API_KEY=your_langchain_api_key
🔑 Note: LangChain API key is needed to enable LangSmith tracing for debugging. You can get your key here.

### Run the App
  Make sure Ollama is installed and running.
  streamlit run app.py
