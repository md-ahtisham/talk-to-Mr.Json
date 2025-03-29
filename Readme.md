#welcome to "Talk to Mr.Json". A Question Answering System for Private Enterprise Data 🔍

## 📚 Introduction

Retrieval-Augmented Generation (RAG) is revolutionizing how companies leverage their institutional knowledge. This project implements a RAG system that empowers organizations to unlock insights from their private internal data while maintaining data privacy and security.

### What is RAG?

RAG combines two powerful components:
1. **Retrieval**: Efficiently extracts relevant documents from your company's internal knowledge base
2. **Generation**: Uses advanced language models to create precise, contextual responses

### Business Value
- **Knowledge Discovery**: Quickly find relevant past projects and experiences
- **Informed Decision Making**: Learn from historical successes and failures
- **Productivity Enhancement**: Reduce time spent searching through documentation
- **Institutional Memory**: Preserve and easily access organizational knowledge
- **Privacy-First**: Process sensitive data locally within your network

## 🌟 Features

- **Smart Document Processing**: Efficiently handles any type of file(e.g doc exls, pdf, csv, etc) internal project documentation
- **Vector Search**: Uses RetrievalQA from langfchain QA_chain for lightning-fast similarity search
- **Context-Aware Responses**: Maintains conversation history for better understanding
- **Structured Output**: Organized response format :
- **Privacy-Focused**: Runs LLM operations within your infrastructure
- **hybird retrieval**: use advance techniqe BM25 + embedding retrieval. 


## 🛠️ Technologies Used


- LangChain - LLM Framework
- chorma - Vector Database
- huggingface - Embeddings
- Gemini - LLM Provider
- BM25 - hybird vecter secarch cobined with retieveal data by retrival 

## 📋 Prerequisites

- Python 3.8 or higher
- Google API Key

## 🚀 Installation & Running



1. **Set up virtual environment**
   ```bash
   python -m venv venv

   # Windows
   .\venv\Scripts\activate

   # Linux/MacOS
   source venv/bin/activate
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure environment variables**  
   Create a `.env` file in the project root:
   ```env
   or directly paste 
   GOOGLE_API_KEY="your_google_api_key_here"
   ```


## 💻 Using the Application

1. Upload your text file using the file uploader
2. Wait for the knowledge base to be created
3. Start asking questions in the chat interface
4. View responses showing:
   - Questions 
   - Answers 
  
