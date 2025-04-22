# 🔍 SimilarWordsFinder

**SimilarWordsFinder** is a lightweight, interactive web application that lets users input a word and retrieve semantically similar words based on vector embeddings. Powered by **LangChain**, **FAISS**, and **OpenAI Embeddings**, this project demonstrates fast and intuitive semantic search over a CSV dataset — all within a clean and friendly **Streamlit** interface.

---

## 🚀 Features

- 🔤 Upload and process a list of words from a CSV file
- 🤖 Use OpenAI's embedding models to understand word semantics
- ⚡ Perform fast similarity search using FAISS vector store
- 💬 Intuitive user input and real-time matching results
- 🧠 Great for educational tools, language learning, and NLP demos

---

## 🛠️ Tech Stack

- **Python 3.10+**
- [Streamlit](https://streamlit.io/) – UI framework  
- [LangChain](https://www.langchain.com/) – Orchestration and document loading  
- [FAISS](https://github.com/facebookresearch/faiss) – Vector similarity search  
- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) – Word representation  
- [dotenv](https://pypi.org/project/python-dotenv/) – Secure API key management  

---

## ⚙️ How to Run the Project

To get started with **SimilarWordsFinder**, follow these simple steps in your terminal:

1. **Install all dependencies**  
```bash
pip install -r requirements.txt
```

2. **Set your OpenAI API Key**  
Create a `.env` file in the project root and add your key:
```
OPENAI_API_KEY = "your_openai_api_key_here"
```

3. **Run the application with Streamlit**
```bash
streamlit run app.py
```

Now you're ready to input a word and explore similar terms!

