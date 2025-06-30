\# 📚 Multi-PDF RAG Chatbot using LLaMA 3 (Local)



This is a simple GenAI project that lets you \*\*chat with multiple PDFs\*\* using a \*\*locally hosted LLaMA 3 model\*\* via Ollama. It performs \*\*PDF text extraction, embedding with FAISS\*\*, and uses \*\*LangChain RetrievalQA\*\* for intelligent question-answering — all offline!



!\[Output Screenshot](output.png)



---



\## 🛠️ Tech Stack



\- Python 3.10  

\- \[LangChain](https://github.com/langchain-ai/langchain)  

\- \[Ollama](https://ollama.com/) with `llama3` model  

\- FAISS (for vector search)  

\- PyMuPDF (`fitz`) for PDF text extraction  

\- `.env` for model config



---



\## 🚀 How to Run



1\. ✅ Make sure you have `ollama` installed and running locally:



&nbsp;  ollama run llama3



✅ Install dependencies:



pip install -r requirements.txt



✅ Place your PDFs in the data/ folder.



✅ Run the app:

python app.py





\##💬 Ask questions about the PDFs!



\##🔮 Future Enhancements:


🌐 Web Interface using Flask / Streamlit



⚡ Fast embeddings using InstructorXL, BGE, or GGUF models



🔁 Support live PDF uploads



🤝 Integrate with Chat history and memory



📦 Dockerize and deploy on GCP / AWS for scalable use



🧠 Add summarization, keyword extraction, and PDF insights as tools

##👨‍💻 Developed by

Guru Sai Sashank

Built as part of a GenAI portfolio.

