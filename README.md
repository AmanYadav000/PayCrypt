# 💳 PayCrypt - AI-Powered Financial Tools

This project is a unified platform that leverages **Generative AI**, **Voice Recognition**, **Fraud Detection**, **Homomorphic Encryption**, and **Semantic Search** for intelligent financial operations. Built with **Streamlit**, **Google Gemini**, **LangChain**, **Transformers**, and **FAISS**, this project demonstrates how multiple cutting-edge technologies can work together to build a futuristic fintech tool.

---

## 🚀 Features

### 🔧 1. Payment Code Generator (AI-Based)
- Generates ready-to-use code for integrating **Stripe**, **PayPal**, or **Razorpay**
- Supports **Python**, **Node.js**, and **Java**
- Takes **custom user instructions**
- Powered by **LangChain + Google Gemini (Gemini 1.5 Pro)**

---

### 🧠 2. Voice-Activated AI Assistant
- Click a button and **speak your query**
- Uses `SpeechRecognition` to convert speech to text
- Checks a **local knowledge base JSON** for answers
- Falls back to **Gemini Pro** if answer is not found
- Learns over time by updating `gemini_payment_knowledge_base.json`

---

### 🔍 3. Real-Time Fraud Detection System
- Simulates streaming transaction data
- Uses **Isolation Forest** model to detect anomalies
- Applies **MinMaxScaler** to normalize features
- Calculates **Risk Score** for each transaction
- Raises alert if risk score > 90
- Displays table of real-time transactions with fraud labels

---

### 🔐 4. Secure Transaction Embedding & Retrieval
- Reads data from `fraud_data.csv`
- Encrypts `amount` using **Paillier Homomorphic Encryption**
- Decrypts only during display or reasoning
- Uses **MiniLM Sentence Transformer** to embed semantic info
- Builds **FAISS** index for similarity search
- Retrieves past similar cases for each query
- Uses **T5 Transformer** model to generate fraud analysis and probability

---

## 📁 File Structure

