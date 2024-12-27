# Chat with PDF using Gemini 💁

This project allows you to **chat with PDF documents** using Google's **Gemini AI**. It processes uploaded PDF files, extracts their content, and answers user questions based on the extracted data. The application is built with **Streamlit** for the user interface and **Google Generative AI** for natural language processing.

---

## 🚀 Features

- 📄 **Upload PDF Files**: Easily upload multiple PDF files for processing.
- 🔍 **Ask Questions**: Query the content of the uploaded PDFs in natural language.
- 🤖 **AI-Powered Responses**: Utilizes Google's Gemini AI for generating accurate answers.
- ⚡ **Fast Search**: Efficiently searches through PDF content using vector embeddings and FAISS indexing.
- 🛠 **Interactive UI**: Simple and interactive interface built with Streamlit.

---

## 🛠️ Tech Stack

- **Python** - Core programming language.
- **Streamlit** - For creating the interactive web application.
- **Google Generative AI** - AI model for question answering.
- **LangChain** - Framework for managing AI chains and embeddings.
- **PyPDF2** - Extracts text from PDF files.
- **FAISS** - Vector similarity search for fast query processing.
- **dotenv** - Environment variable management.

---

## 📦 Installation

1. **Clone the Repository:**
```
git clone https://github.com/username/repository-name.git
cd repository-name
```

2. **Create Virtual Environment (Optional):**
```
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies:**
```
pip install -r requirements.txt
```

4. **Set Up Environment Variables:**
- Create a `.env` file in the root directory.
- Add your **Google API Key**:
```
GOOGLE_API_KEY=your-api-key-here
```

---

## ▶️ Usage

1. **Run the App:**
```
streamlit run app.py
```

2. **Upload PDFs:**
- Use the sidebar to upload PDF files.

3. **Ask Questions:**
- Type questions related to the uploaded PDFs in the input box.

4. **Get Responses:**
- View AI-generated responses instantly.

---

## 🧪 Example Queries
- *"What are the key points discussed in the uploaded document?"*
- *"Summarize the introduction section."*
- *"Explain the methodology described in the document."*

---

## 📄 Requirements

```
streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
faiss-cpu
langchain_google_genai
```

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📧 Contact
For any inquiries, please reach out to me at:
- **Email**: moaazhammad36@gmail.com

---



## 🌟 Acknowledgements
- **Streamlit** for the web interface.
- **Google Generative AI** for AI-powered responses.
- **LangChain** for seamless AI integration.
- **FAISS** for vector-based search.

