# 🤖 EmpathyBot - Sentiment-Aware Chat with RAG & Few-Shot Prompting

EmpathyBot is an **emotion-aware chatbot** that detects the user's emotions and generates empathetic responses.  
It combines **emotion classification (DistilBERT)** with a **RAG-style retrieval system (FAISS + Sentence-Transformers)** to provide relevant, context-sensitive replies.

---

## 🚀 Features
- **Emotion Detection** using [`bhadresh-savani/distilbert-base-uncased-emotion`](https://huggingface.co/bhadresh-savani/distilbert-base-uncased-emotion).  
- **Semantic Retrieval (RAG)** with [`all-MiniLM-L6-v2`](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2).  
- **Few-Shot Prompting**: predefined empathetic templates per emotion.  
- **Interactive UI** built with **Streamlit** (WhatsApp-style chat design).  
- **Ngrok Tunneling** for easy public deployment.  
Google Drive for Demo :
https://drive.google.com/drive/folders/1sjNTicQS6ycsTgAETt1Nkdpf2Wm4vDLs?usp=drive_link
