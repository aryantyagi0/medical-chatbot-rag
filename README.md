# Medical Chatbot with RAG

A smart medical chatbot that uses **Retrieval-Augmented Generation (RAG)** to provide accurate answers from medical documents such as PDFs.

---

## 🧩 Project Structure

medical-chatbot-rag/

├── data/ # Folder containing medical documents
│ └── medical_book.pdf
├── vectorstore/ # Vector database for RAG
│ └── db_faiss/
│ ├── index.faiss
│ └── index.pkl
├── README.md # Project documentation

---

## ⚡ Features

- Upload medical documents (PDFs) to create a **knowledge base**.  
- Chat with the bot to get **relevant answers**.  
- Uses **FAISS vector embeddings** for fast and efficient information retrieval.  
- Easy to extend with other NLP models or additional documents.  

---

## 🛠 Tech Stack

- **Python**  
- **LangChain** for RAG pipeline  
- **FAISS** for vector storage and similarity search  
- **Streamlit** (optional, for user interface)  
- **Hugging Face Hub** for pre-trained models  

---

## 🚀 Installation & Setup

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/medical-chatbot-rag.git
cd medical-chatbot-rag
Create a virtual environment (recommended):
python -m venv venv
# Activate it
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
Install required packages:
pip install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pip install huggingface_hub
📝 Usage

Place your medical documents (PDFs) inside the data/ folder.

Make sure the vectorstore (vectorstore/db_faiss/) is updated with FAISS indices.

Run the chatbot
Interact with the chatbot to ask medical queries. The bot retrieves relevant information from your documents.
.

📧 Contact

Created by Aryan Tyagi.
Feel free to open issues or contribute to the project.
