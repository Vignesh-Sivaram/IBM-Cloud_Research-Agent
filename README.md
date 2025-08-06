# IBM-Cloud_Research-Agent
AI Research agent assisting users in academic and scientific research tasks

# 📚 AI-Based Research Assistant using IBM Watsonx

An intelligent AI assistant designed to support academic and scientific research tasks such as literature search, paper summarization, hypothesis generation, and research report drafting. Built using IBM Watsonx Assistant and integrated with granite foundational model.

---

## 🧠 Project Overview

Academic researchers often spend significant time manually searching for literature, organizing references, and drafting research papers. This project aims to automate these tasks using instruction-tuned large language models (LLMs) provided by IBM Watsonx.

---

## 🚀 Features

- 🔍 Semantic search of academic papers via databases
- 🧾 Summarization of paper abstracts
- 📖 Drafting structured research sections (Introduction, Literature Review, etc.)  
- 🧠 Suggests hypotheses based on user queries  

---

## 🛠 System Requirements

- OS: Windows 10 / macOS / Linux  
- RAM: 8 GB (16 GB recommended)  
- Python: 3.8+ (for backend or testing tools)  
- IBM Cloud Account with Watsonx Assistant (Free or Lite plan)  
- Internet connection (for API calls and deployment)

---

## 🧰 Tools and Technologies

- **IBM Watsonx Assistant** - LangGraph / ReAct architecture  
- **Granite-3-3-8b-instruct** LLM  

---

## 🧑‍💻 Setup Instructions

### 1. Create a Watsonx Assistant
- Go to [IBM Watsonx](https://www.ibm.com/watsonx)
- Create a new **Assistant** under Agent Builder
- Choose **LangGraph or ReAct** architecture
- Add base model: `granite-3-3b-instruct` or similar

### 2. Prompt Instructions for Assistant
```
You're a helpful AI assistant that assists users in academic and scientific research tasks. Greet the user, ask for the field of research,
and search for relevant literature. Summarize papers, organize references, and help draft research sections. Use a respectful, formal tone and support APA/MLA/IEEE styles.
```
Interface of Assistant:
<img width="1900" height="868" alt="Screenshot 2025-08-05 005405" src="https://github.com/user-attachments/assets/b98925c2-d869-4269-ab3b-d332f41a7d93" />

