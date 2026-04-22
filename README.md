# AutoStream AI Agent 🚀

This project is a simple conversational AI agent built for a SaaS product called **AutoStream**.

The goal of this agent is to:
- Answer user questions about pricing and features
- Detect when a user is interested in buying
- Collect user details (name, email, platform)
- Simulate lead capture

---

## 🧠 How it works

The agent follows a simple flow:

1. User asks about plans → agent responds using a local knowledge base  
2. If user shows interest (e.g., "I want Pro plan") → agent starts signup flow  
3. Agent collects:
   - Name  
   - Email  
   - Platform  
4. After collecting all details → lead is captured using a mock function  

---

## 📁 Project Structure
 app.py → main chatbot logic
intent.py → detects user intent
rag.py → handles knowledge-based responses
memory.py → manages conversation state
tools.py → lead capture function

## Example

You: Hi
Bot: Hi! Welcome to AutoStream 🚀

You: Tell me plan
Bot: Basic Plan: $29/month...

You: I am interested in Pro plan for YouTube
Bot: Great! Let's get you started. What's your name?

You: Amrish
You: amrish@gmail.com

You: YouTube

Bot: Lead captured successfully...
