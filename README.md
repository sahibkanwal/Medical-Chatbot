# Medical Chatbot with LangChain, Pinecone, Flask, and AWS

## Overview
This project is a medical question-answering chatbot that uses LangChain for orchestration and Pinecone for semantic search. It is built with Flask and can be deployed on AWS for scalability. The chatbot provides context-aware answers to health-related queries.

**Note:** This project is for educational purposes only and is not a substitute for professional medical advice.

---

## Features
- LLM-powered medical Q&A with retrieval
- LangChain for managing prompts and workflows
- Pinecone for vector storage and similarity search
- Flask backend with REST API
- AWS deployment ready

---

## Tech Stack
- **Backend:** Python, Flask  
- **AI/ML:** LangChain, Hugging Face embeddings  
- **Database:** Pinecone  
- **Deployment:** AWS, dotenv  

---

## Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/medical-chatbot.git
cd medical-chatbot

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

The app will run locally at: **http://127.0.0.1:5000/**

---

## Example
**Q:** What are the symptoms of pneumonia?  
**A:** Common symptoms include cough, fever, and difficulty breathing. Please consult a doctor for medical advice.

---

## Acknowledgments
Built with LangChain, Pinecone, Flask, and AWS.  
Developed by Sahib Kanwal.  
