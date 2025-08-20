# Simple Chatbot with Open Source LLMs – BlenderBot + Python

Simple Chatbot with Open Source LLMs, it’s a practical, production-ready chatbot that brings human-like conversational AI to your terminal.  
Built with **Facebook BlenderBot 400M (distilled)** and Hugging Face Transformers, this project demonstrates how easy it is to run a modern, open-source language model on your own machine.

---

## Why This Project Matters
Conversational AI is transforming how humans interact with technology, from customer support to education, personal productivity, and beyond.  
This project shows how **anyone** can build a chatbot using open-source Large Language Models (LLMs) with just a few lines of Python.

Real-world applications include:
- **Customer Support**  Automate FAQs and common requests with a conversational interface.  
- **Education** Provide students with a 24/7 assistant to answer questions.  
- **Personal Productivity**  Use the chatbot as a note-taker, brainstorming partner, or writing helper.  
- **Prototyping AI Products**  Kickstart your own chatbot app, Slack bot, or website assistant.  
- **Learning & Research**  Understand how conversational models work under the hood.  

---

## Key Features
- **Open Source LLMs** – Powered by `facebook/blenderbot-400M-distill`.  
- **Lightweight & Fast** – Runs locally on CPU (GPU optional for speedup).  
- **Conversation Memory** – Maintains dialogue context across turns.  
- **Minimal Setup** – No complex frameworks, just plain Python + Hugging Face.  
- **Extendable** – Use as a base for chatbots in web apps, APIs, or messaging platforms.  

---

## Quickstart
## Run the Chatbot (Terminal)


### Clone & Setup
```bash
git https://github.com/Hadeer-Nabil/Simple-Chatbot-with-OpenSource-LLMs.git
cd simple-chatbot-llm

python -m venv .venv
source .venv/bin/activate   

pip install --upgrade pip
python3 -m pip install transformers==4.30.2 torch 
```

## Run the Chatbot (Terminal)
```bash
python chatbot.py
```