# 🛡️ Legal Document analyser using RAG
---

## 🚀 Tech Stack

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)

---


## ✨ Key Features

### 🤖 **AI-Powered Document Intelligence**
- **Smart Summarization**: Get concise summaries of dense legal documents in simple language.
- **Clause Explanation**: Understand contract clauses and their potential impact instantly.
- **Risk Assessment**: Automatically flag potential compliance risks within your documents.
- **Multi-format Support**: Process documents in various formats like PDF, DOCX, and TXT.

### 📊 **Compliance Engine**
- **Multi-Jurisdiction Support**: Check compliance against multiple regulations: GDPR (EU), PDPA (MY/SG), CCPA (US), Employment Act (MY).
- **Real-time Compliance Checking**: Validate documents against legal frameworks on the fly.
- **Risk Scoring**: Receive a quantifiable compliance risk score on a 0-100 scale.
- **Regulatory Alerts**: Get notified about potential compliance gaps proactively.

### 💼 **Enterprise-Grade Features**
- **Export Capabilities**: Generate and share PDF reports with stakeholders.
- **RESTful API**: Integrate with your existing software using our API.
- **Comprehensive Documentation**: Access auto-generated API documentation via OpenAPI/Swagger.


---



### **🎯 Key UI Components**

| Component | Purpose | Features |
|-----------|---------|----------|
| **Landing Page** | Initial user touchpoint & introduction | Hero section, feature overview, call-to-action |
| **Authentication** | Secure user access | Login/signup functionality and protected application routes |
| **Dashboard** | Main user workspace | Overview of analytics, recent activity, and quick actions |
| **Document Analyzer** | Primary analysis tool | File upload (including drag & drop) and text input for analysis |
| **AI Insights** | AI-driven analysis results | Displays summaries, clause explanations, and risk scores |
| **Compliance Center** | Compliance status overview | View compliance status across different legal jurisdictions |
| **Reports & Export** | Data reporting and sharing | PDF generation with data visualizations |




## 🎮 Quick Start Demo

### **1. Clone & Setup**
```bash
# Clone the repository
git clone https://github.com/Soham508/Legal-document-analysis-and-regulatory-compliance-using-RAG.git
cd Legal-document-analysis-and-regulatory-compliance-using-RAG

# Backend setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8000

# Frontend setup (new terminal)
cd ../frontend
npm install
npm run dev

# .env setup
create .env file inside backend/ directory
add following - 
WATSONX_API_KEY: Your IBM Cloud API key.
WATSONX_PROJECT_ID: The project ID for your WatsonX.ai project.
WATSONX_URL: The API endpoint for the WatsonX.ai service.
```


### **4. UI Feature Showcase**
```bash
# Open the application and explore:
# 🏠 Landing Page - The main entry point of the application.
# 📊 Dashboard - Get a quick overview of your document analytics.
# 📄 Document Analyzer - Upload and analyze your legal documents.
# 🤖 AI Insights - View AI-generated summaries and explanations.
# 📋 Compliance Center - Check compliance against various regulations.
# 📈 Reports - Generate and export analysis reports.
```

---
