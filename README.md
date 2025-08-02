# Chronic-Disease-Monitoring-AI-Agent
## 🏥 ChronicCare AI Assistant
An AI-powered medical assistant designed to help users understand, manage, and monitor chronic diseases such as diabetes, hypertension, asthma, heart disease, and more. Built using IBM watsonx.ai with Retrieval-Augmented Generation (RAG) and IBM cloud tools, this agent delivers accurate, empathetic, and document-grounded healthcare guidance.

## 🧩 Problem Statement
Millions of people suffer from chronic illnesses without proper awareness or support. Many lack timely information about symptoms, medication, diet plans, risk factors, and preventive measures. This leads to complications, hospitalizations, and increased health costs.

## 💡 Proposed Solution
An intelligent medical AI agent built on IBM watsonx.ai that provides trustworthy, document-supported answers and healthcare tips. It retrieves context from medical documents using Vector Indexing and responds in clear, simple language. Ideal for patients, caregivers, and health educators.

## 🧠 Technologies Used
- 🧠 IBM Watsonx.ai Studio
- 🧬 LLaMA 3-3-70B Instruct Model
- 📚 Vector Index for RAG (Retrieval-Augmented Generation)
- 📝 Medical data from curated .txt file
- 🧠 Natural Language Processing
- ☁️ IBM Cloud Object Storage

## ☁️ IBM Cloud Services Used
- IBM Watsonx.ai Studio
- LLaMA 3-3-70B Instruct Model
- Watsonx Vector Index
- IBM Cloud Lite Account
- IBM IAM & Deployment Spaces
- Cloud Object Storage

## 👥 End Users
- Patients with chronic conditions
- Family caregivers
- General public seeking health advice
- Rural and semi-urban citizens
- Health educators and NGOs
- Schools and community outreach groups

## 🌟 WOW Factors
- ✅ Uses Retrieval-Augmented Generation (RAG) from real medical documents
- 🌐 Answers based on chronic_disease_info.txt file using vector search
- 🧠 Empathetic & safe response design (avoids wrong medical guesses)
- 🌍 Future-ready for multilingual & speech input
- 🩺 Covers real health topics: symptoms, lifestyle, diet, prevention
- 🔒 Keeps patient education safe, simple, and private

## 🧪 Key Features
- Vector-based document search from medical text
- Handles chronic disease FAQs: diabetes, BP, asthma, heart, arthritis
- Supports internet search fallback (Google)
- Prevents wrong answers on unrelated topics with polite redirection
- Conversational interface preview within IBM watsonx.ai
- Based entirely on IBM's trusted tools

## 🚀 How It Works
- User types a question (e.g., “How to prevent diabetes complications?”)
- LLaMA 3 LLM interprets the intent
- IBM Vector Index pulls relevant answers from uploaded medical text
- AI responds in simple, structured, and safe language

## 📌 How to Run or Deploy
- Log in to IBM Cloud Lite: https://cloud.ibm.com
- Launch Watsonx.ai Studio
- Create a new AI Agent
- Upload financial PDFs to a Vector Index
- Choose Tools for web search (Google,Wikipedia,DuckDuckGo etc..)
- Configure agent instructions and topics (restricting AI from answering off-topic questions politely)
- Test in the preview panel
- Deploy via web snippet, Streamlit, or custom web UI

## 🛣️ Future Scope
- 🌍 Multilingual support using Watson Language Translator
- 🗣️ Voice input via Speech-to-Text API
- 📲 Integration with WhatsApp or Mobile App
- 📅 Daily/Weekly health reminders
- 📈 Monthly chronic health progress reports
- 📘 Disease-specific modules (e.g., for CKD, arthritis, etc.)

## 🔗 Useful Links
- IBM Cloud
- Watsonx.ai Studio Docs
- WHO – Chronic Illness
- CDC – Chronic Disease Info
- IBM SkillsBuild

## ⚖️ License
This project is licensed under the MIT License.

## 🙋‍♀️ Created By
Bindu Sundarapu
Created as part of IBM SkillsBuild for Academia Internship 2025

