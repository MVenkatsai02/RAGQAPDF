# 📚 Conversational RAG with PDF Uploads and Chat History

An AI-powered Streamlit application that allows users to upload PDFs and engage in a conversation with their content using Retrieval-Augmented Generation (RAG). The system keeps track of chat history and provides context-aware responses using LangChain, FAISS, and Hugging Face embeddings.

## 🛠️ Features

✅ Upload PDFs and retrieve insights from their content

✅ Conversational RAG with chat history awareness

✅ Uses FAISS for efficient document retrieval

✅ Powered by Groq API and Hugging Face embeddings

✅ Streamlit-based interactive UI

## 📂 Project Structure

```bash
conversational-rag/
├── app.py                 # Main Streamlit application
├── .env                   # API key storage (not to be committed)
├── requirements.txt       # List of dependencies
├── README.md              # Documentation
└── .gitignore             # Ignore unnecessary files
```

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MVenkatsai02/RAGQAPDF
cd conversational-rag
```

### 2️⃣ Set Up a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 🖥️ Running Locally

### 🔹 Start Streamlit Application

```bash
streamlit run app.py
```

Your UI will be available at:

👉 http://localhost:8501

## 🌍 Deployment

### 4️⃣ Deploy on Streamlit Cloud

1. Push the project to GitHub.
2. Go to Streamlit Cloud → Click "Deploy an App".
3. Select GitHub repo → Set main file path to `app.py`.
4. Deploy and share your app link.

## 📌 Example Usage

1️⃣ Open the Streamlit UI.

2️⃣ Upload a PDF document.

3️⃣ Ask questions about the document's content.

4️⃣ View AI-generated responses with context awareness.

## 🔧 Troubleshooting

💡 **Issue: API Key Not Found**
✔️ Ensure `.env` file contains:
```
huggingface_api_key=your_hf_key
groq_api_key=your_groq_key
```
✔️ Restart the Streamlit app after updating the `.env` file.

💡 **Issue: Missing Dependencies**
✔️ Run `pip install -r requirements.txt`.
✔️ Ensure the virtual environment is activated.

## 🛡️ License

This project is open-source under the MIT License.

## 📩 Contact & Contributions

🔹 Feel free to fork this repo & contribute!

🔹 Found a bug? Create an issue on GitHub.

🔹 Questions? Reach out via email: venkatsaimacha123@example.com

🚀 Built with ❤️ using Streamlit, LangChain, FAISS, and Hugging Face 🚀

