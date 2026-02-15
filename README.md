# NyaaySahayak 🏛️🎙️  
**Empowering rural India with accessible, voice-first legal intelligence**

## Track
AI for Rural Innovation & Sustainable Systems  
AWS AI for Bharat Hackathon

---

## 🚩 Problem Statement
Rural citizens in India face exploitation and exclusion from legal protections because land records, loan agreements, and government notices are written in complex legal English that is inaccessible to semi-literate, non-English-speaking populations.

---

## 💡 Solution Overview
**NyaaySahayak** is a Generative AI-powered, voice-first legal companion designed for rural India.  
It helps users understand legal and government documents by converting them into **simple, spoken explanations in local languages and dialects**.

Users can simply **take a photo of a document**, listen to its explanation, and ask follow-up questions using **natural speech**.

---

## ✨ Key Features
- 📷 **Document Photo Input** – Capture images of legal documents using a mobile phone  
- 📄 **AI-Based Text Extraction** – Reads printed and handwritten documents  
- 🌾 **Legal Language Simplification** – Converts legal jargon into everyday language  
- 🌐 **Vernacular Translation** – Supports Indian languages and rural dialects  
- 🔊 **Voice-First Output** – Audio explanations instead of text  
- 🎙️ **Conversational Q&A** – Ask follow-up questions using speech  
- 📡 **Low-Bandwidth Optimized** – Designed for rural connectivity conditions  
- 🔐 **Privacy & Guardrails** – Provides legal information only, not legal advice  

---

## 🧠 Why Generative AI?
- Legal language is **contextual**, not literal — rule-based systems fail  
- LLMs preserve legal meaning while simplifying explanations  
- Natural speech and dialect handling require AI, not keyword-based logic  
- Unstructured documents need intelligent layout understanding  

---

## 🏗️ System Architecture (High-Level)
1. User uploads a document image via a mobile/web app  
2. Text is extracted using **Amazon Textract**  
3. Legal content is simplified using **Amazon Bedrock (Claude 3)**  
4. Output is translated into local languages  
5. Explanation is converted to speech using **Amazon Polly**  
6. Voice queries are handled using **Amazon Transcribe + Bedrock**

---

## ☁️ AWS Technology Stack
- **Frontend:** React / Next.js PWA (AWS Amplify)  
- **Backend:** API Gateway + AWS Lambda  
- **OCR:** Amazon Textract  
- **AI Reasoning:** Amazon Bedrock (Claude 3)  
- **Translation:** Amazon Translate  
- **Speech-to-Text:** Amazon Transcribe  
- **Text-to-Speech:** Amazon Polly  

---

## 🛡️ Responsible AI & Privacy
- Guardrails ensure the system provides **information, not legal advice**  
- Users are clearly warned to consult a lawyer for critical decisions  
- No document data is stored permanently  
- Neutral, factual responses to prevent misinformation  

---

## 🌍 Impact
- Improves legal literacy in rural communities  
- Prevents exploitation and unfair contracts  
- Increases access to government schemes  
- Promotes inclusive and sustainable rural development  

---

## 📄 Documentation
- [`requirements.md`](./requirements.md) – Functional and non-functional requirements  
- [`design.md`](./design.md) – System design and architecture  

---

## 👥 Team
**Project Name:** NyaaySahayak  
**Team:** CoreX  
**Team Lead:** Ayushman Swain

---

## 🚀 Status
Prototype / Hackathon Submission  

