# 🏛️ Constitution Study Chatbot

**An AI-powered chatbot designed for law students to study the Egyptian Constitution efficiently.** 📜

## 🚀 Overview

The **Constitution Study Chatbot** is an AI-based system that allows law students to upload the Egyptian Constitution in PDF format and query it using natural language. It utilizes **retrieval-augmented generation (RAG)** to enhance search accuracy, providing detailed responses based on legal documents. 

🔹 **Technologies Used**  
- **Backend**: FastAPI  
- **Frontend**: Streamlit  
- **Storage**: ChromaDB  
- **Querying & Retrieval**: LlamaIndex  
- **AI Model**: RAG-based approach  

---

## 📌 Features

✅ **Upload & Search** – Users can upload a PDF of the Egyptian Constitution and perform AI-powered queries.  
✅ **Real-time Interactions** – The chatbot provides quick and accurate responses.  
✅ **Efficient Storage** – Uses **ChromaDB** for vector-based document retrieval.  
✅ **Optimized Query Processing** – Powered by **LlamaIndex** to enhance search accuracy.  
✅ **User-friendly Interface** – Simple and intuitive UI built with **Streamlit**.  

---

## 🛠️ Installation & Setup

Follow these steps to set up the project on your local machine:

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Abodzaa/Constitution-Study-Chatbot.git
cd Constitution-Study-Chatbot
```

### 2️⃣ Create a Virtual Environment  
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### 3️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Backend (FastAPI)  
```bash
uvicorn endpoint:app --reload
```

### 5️⃣ Run the Frontend (Streamlit)  
```bash
streamlit run ui.py
```

---

## 📂 Project Structure  

```
📦 Constitution Study Chatbot
 ┣ 📜 constitution.pdf      # Egyptian Constitution PDF
 ┣ 📂 temp                  # Temporary storage
 ┣ 📄 endpoint.py           # FastAPI backend
 ┣ 📄 ui.py                 # Streamlit frontend
 ┣ 📄 ingest.py             # PDF processing
 ┣ 📄 utils.py              # Helper functions
 ┣ 📄 model.py              # AI model integration
 ┣ 📜 requirements.txt      # Project dependencies
 ┣ 📜 readme.md             # Project documentation
 ┗ 📂 __pycache__           # Python cache files
```

---

## 👥 Contributors

- **Abdelrahman Ismail** – AI Developer, Backend Engineer  
- **Your Team Members** (if any)  

---

## 📌 Future Improvements  

🔹 Expand the chatbot to support multiple legal documents 📑  
🔹 Enhance NLP capabilities for more complex queries 🤖  
🔹 Deploy the project to cloud services for wider accessibility ☁️  

---

## ⭐ Acknowledgments  

This project was developed as part of the **Digital Egypt Pioneers Initiative (DEPI) - Generative AI Professional Track**.

---

## 📢 License  

This project is **open-source** under the [MIT License](LICENSE).  

If you find this project helpful, consider giving it a ⭐ on GitHub!  

🔗 **GitHub Repository**: [Constitution Study Chatbot](https://github.com/Abodzaa/Constitution-Study-Chatbot)  
