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



###  Create a Virtual Environment (Python 3.10)
# On Windows:
  conda create -p venv python==3.10
# On macOS/Linux:
  source venv/bin/activate
### Install required packages
  pip install -r requirements.txt

### Create a .env file in root:
  LANGCHAIN_API_KEY=your_langchain_api_key
🔑 Note: LangChain API key is needed to enable LangSmith tracing for debugging. You can get your key here.

### Run the App
  Make sure Ollama is installed and running.
  streamlit run app.py

![Screenshot 2025-05-19 150945](https://github.com/user-attachments/assets/4cb9e96b-9e74-4d30-902f-36baf59a7448)
![Screenshot 2025-05-19 151028](https://github.com/user-attachments/assets/66d603a6-0192-47ef-936c-6a6971d92136)
![Screenshot 2025-05-19 151213](https://github.com/user-attachments/assets/0471e3b6-dbcc-4d25-89c3-4628a81b6eba)
![Screenshot 2025-05-19 151433](https://github.com/user-attachments/assets/8faa2ac1-595c-41fa-b9c1-c5e8fe366194)
![Screenshot 2025-05-19 151449](https://github.com/user-attachments/assets/61b5ca04-14be-423b-ba69-438606335099)



