# Day 1 – AI Agents Training

## Project: Sweet Crumbs Home Bakery Assistant

### Overview
This project implements an AI-powered customer support assistant for Sweet Crumbs Home Bakery using Python, LangChain, and Groq.

The assistant helps customers by answering questions about bakery products and order policies.

### Technologies Used
- Python
- LangChain
- Groq API
- Large Language Models (LLMs)

### Features
- AI-powered customer interaction.
- Bakery-specific system prompt.
- Provides information about bakery orders.
- Supports eggless cake inquiries.
- Follows predefined business rules.
- Maintains friendly and concise responses.

### Business Rules
1. All products are baked to order.
2. Orders require 24 hours' notice.
3. All cakes have eggless versions.
4. The assistant should never promise delivery times.
5. If information is unavailable, the assistant should respond appropriately.
6. Responses should be polite and under 60 words.

### Installation

Install the required dependency:

```bash
pip install langchain-groq
```

### API Configuration

Set your Groq API key as an environment variable.

Windows PowerShell:

```powershell
$env:GROQ_API_KEY="your_api_key"
```

### How to Run

```bash
python agenticAI_Day1.py
```

### Learning Outcomes
- Understanding AI agents and LLMs.
- Working with LangChain.
- Integrating Groq API.
- Writing effective system prompts.
- Building a simple AI-powered chatbot.

### Conclusion
Day 1 demonstrates how to build a basic AI-powered bakery customer support assistant using Python, LangChain, and Groq.
