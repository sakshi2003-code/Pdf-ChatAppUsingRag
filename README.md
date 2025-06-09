# PDF Chat Application Using Retrieval-Augmented Generation (RAG)

A conversational AI application that allows users to upload PDF documents and interact with their content using Retrieval-Augmented Generation (RAG) techniques. This project leverages advanced NLP models to provide accurate and context-aware answers based on the uploaded PDFs.

## 🚀 Features

- Upload one or multiple PDF files  
- Extract and index PDF content for quick retrieval  
- Chat interface to ask questions about the document content  
- Context-aware responses powered by RAG and large language models  
- Easy-to-use, interactive UI

## 🛠 Technologies Used

- Python  
- LangChain / Hugging Face Transformers  
- Ollama (or other LLM APIs)  
- Streamlit (for web interface)  
- PDF parsing libraries (e.g., PyPDF2 or pdfplumber)  

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshi2003-code/Pdf-ChatAppUsingRag.git
   cd Pdf-ChatAppUsingRag
````

2. Create a virtual environment and activate it:

   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. install ollama model locally.

## ⚙️ Usage

Run the Streamlit app locally:

```bash
streamlit run app.py
```

Open your browser and go to `http://localhost:8501` to interact with the app.

Upload your PDF documents, then ask questions related to the content.

## 📂 Project Structure

* `app.py` — Main Streamlit application
* `pdf_utils.py` — PDF parsing and text extraction utilities
* `rag_pipeline.py` — Retrieval-Augmented Generation pipeline logic
* `requirements.txt` — Project dependencies

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, bug fixes, or new features.

Please ensure your code follows the existing style and includes appropriate tests.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

If you find this project useful, please ⭐ the repo!

---

*Created by Sakshi Bijalwan*
[GitHub Profile](https://github.com/sakshi2003-code) | [LinkedIn](https://www.linkedin.com/in/sakshi-bijalwan/)



