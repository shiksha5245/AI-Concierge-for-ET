# AI-Concierge-for-ET

ET AI Concierge System

An intelligent multi-agent AI concierge system designed for the Economic Times (ET) ecosystem.
This system understands user intent, routes queries to specialized AI agents, and provides personalized financial guidance, product recommendations, and services.

 Project Overview

The ET AI Concierge solves the problem of low product discovery by:
Understanding users in real-time
Providing personalized financial insights
Recommending ET products & services
Enabling cross-sell and marketplace integration

Core Features

 1. Multi-Agent AI System
Intelligent Router Agent for intent detection
Specialized agents:
Welcome Concierge
Financial Navigator
Cross-Sell Engine
Marketplace Agent

 2. Memory + Context Awareness

FAISS Vector Database for semantic memory
Stores conversation embeddings
Retrieves relevant past context using similarity search

 3. Gemini AI Integration

Uses Gemini 2.5 Flash
Handles:
Reasoning
Natural language understanding
Personalized responses

 4. Real-Time Chat UI

Built using Gradio
Interactive chatbot interface
Supports dynamic conversation flow

 5. Metrics Tracking

Tracks:

Sessions
Messages
Conversions
Stored in JSON for analytics

System Architecture
The system is designed as a layered 

multi-agent architecture:

Layers:

User Interface (Chatbot)
Router Agent (Intent Detection)
Specialized Agents
Core AI Engine (LLM + Vector DB)
Storage & External APIs

 Tech Stack

AI Model: Gemini 2.5 Flash
Backend: Python
UI: Gradio
Vector DB: FAISS
Embeddings: Sentence Transformers
Data Handling: Pandas, NumPy
Visualization: Matplotlib, Graphviz

How to Run

1. Install Dependencies

pip install google-generativeai gradio faiss-cpu sentence-transformers pandas numpy matplotlib graphviz

2. Add API Key

Python
API_KEY = "YOUR_API_KEY"

3. Run the Project
 Example Queries
"hello"
"I want to invest in stocks"
"Suggest premium tools"
"I need a personal loan"
"Best insurance options"

 Testing

Run built-in test functions:
Python
test_router()
test_agents()
test_memory()
test_full()

 Future Improvements

Voice-enabled AI concierge
Real-time stock data integration
Advanced recommendation engine
Multi-language support (Hindi + regional)
User dashboard analytics
