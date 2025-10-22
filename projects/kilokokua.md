---
layout: project
type: project
image: img/kilokokua.png
title: "KiloKōkua: AI-Powered Climate Chatbot"
date: 2025
published: true
labels:
  - AI Integration
  - FastAPI
  - Vertex AI
  - OpenAPI
  - RESTful API
  - Full Stack Development
summary: "An AI-powered chatbot providing conversational access to Hawaiʻi's climate data through the Hawaiʻi Climate Data Portal."
---

## 🌺 Project Overview

**KiloKōkua** ("Observation Helper") is an AI-powered chatbot that provides easy, conversational access to Hawaiʻi's climate data for residents, students, researchers, and policymakers.  
By leveraging **Google Vertex AI** and the **Hawaiʻi Climate Data Portal (HCDP)**, users can obtain real-time and historical climate insights about any location in Hawaiʻi through natural conversation.

This project was built as part of the **AI Hackathon: Aloha Data** initiative.

---

## 🌦️ About the Hawaiʻi Climate Data Portal (HCDP)

The **Hawaiʻi Climate Data Portal (HCDP)** provides streamlined access to high-quality, reliable climate data and information for the State of Hawai‘i and parts of the Pacific.  
It delivers near-real-time rainfall and temperature maps, gridded datasets, and other environmental variables — supporting researchers, decision makers, and the broader community.

Centralizing these datasets helps promote environmental stewardship and reduces barriers to accessing critical data for analysis and policy development.

---

## 🧠 Chatbot Functionality

- Conversationally retrieves climate data (rainfall, temperature, trends) via **HCDP’s external API**  
- Uses **natural language understanding** to interpret user questions  
- Responds with concise and contextually relevant data summaries  
- Prompts users for additional details when queries are incomplete  
- Designed for embedding within web portals for **intuitive data exploration**

---

## 🧑‍💻 Team & Role

This project was developed collaboratively as part of the **AI Hackathon: Aloha Data** initiative.

**My contributions:**

- **Training and configuring** the chatbot using **Google Vertex AI**, fine-tuning responses for clarity and accuracy  
- **Connecting the chatbot** to the **HCDP external API** via an **OpenAPI Schema** with secure **API token authentication**  
- Implementing **input validation and prompt logic**, enabling the chatbot to detect incomplete user queries and request missing details  
- Ensuring accurate **user intent parsing** to form valid API requests and return precise climate information  
- **Embedding the chatbot** seamlessly into the existing **HCDP website**, enhancing accessibility and engagement

---

## ⚙️ Technical Architecture

### 🧱 Backend Stack
- **FastAPI** – RESTful API framework handling AI service endpoints  
- **SQLAlchemy** – ORM for database interactions (PostgreSQL in production, SQLite in development)  
- **Alembic** – Database migration management  
- **HTTPX** – Async HTTP client for API calls to external services  
- **Custom AI Service Layer** – Abstracted logic for communicating with Vertex AI or fallback models  
- **Docker + Nginx** – Containerized deployment with unified access routing  

---

### 🔐 Security & Configuration
- **JWT Authentication** for secure, stateless user sessions  
- **dotenv** for local development environment variables  
- **Google Cloud Secret Manager** for production secret storage (API keys, DB URLs, JWT signing keys)  
- AI service requests routed **through backend validation layers** (never directly from the frontend)

---

### 🚀 Performance & Scalability
- Built on **Starlette + async I/O**, ensuring rapid response times  
- Modular architecture allows for scalable integration of additional AI services and datasets  

---

## 🧩 Key Takeaways
- Combined **AI conversational interfaces** with **real-world environmental data**
- Strengthened skills in **API integration**, **Vertex AI**, and **secure backend development**
- Developed a scalable, modular solution that bridges **AI**, **data access**, and **climate research**

---

## 🔗 Demo & Repository
- 🌐 **Website (Prototype):** [Hawaiʻi Climate Data Portal](https://www.hawaii.edu/climate-data-portal/)  
- 💻 **GitHub Repository:** *Coming soon*
