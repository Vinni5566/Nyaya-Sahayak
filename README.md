# 🏛️Nyaya Sahayak
Voice-First AI Complaint Assistant for Inclusive Governance

---

## 📌 Problem Statement

Millions of citizens struggle to file formal complaints due to:

- Language barriers  
- Low literacy levels  
- Improper formatting of grievances  
- Lack of clarity on required evidence  
- Complex and fragmented government portals  

As a result, complaints are often rejected, delayed, or unresolved.

Nyaya Sahayak simplifies complaint filing through AI-driven automation and voice-first interaction.

---

## 🎯 Solution Overview

Nyaya Sahayak is a **voice-first, multilingual AI grievance assistant** that simplifies complaint filing through automation and intelligent formatting.

It enables citizens to:

1. **Submit complaints via voice** in their local language  
2. **Automatically convert and structure speech into formal text**  
3. **Classify the complaint type and identify the appropriate authority**  
4. **Generate professionally formatted drafts with evidence suggestions**  
5. **Track status and flag urgent cases for escalation**

The system reduces filing errors, improves acceptance rates, and makes grievance redressal more accessible and inclusive.

---

## ✨ Core Features

- **Voice-First Multilingual Input**  
  Speech-to-text processing using Whisper/Vosk with support for regional languages, designed for accessibility and low-literacy users.

- **AI-Based Classification & Routing**  
  Automatically categorizes complaints and identifies the appropriate authority or department.

- **Automated Complaint Formatting**  
  Converts raw grievances into structured, professionally formatted drafts with evidence suggestions.

- **Learning & Optimization**  
  Improves template quality over time based on successful complaint patterns.

- **Urgency Detection**  
  Identifies critical cases and recommends escalation when necessary.

- **Low-Bandwidth Support**  
  Lightweight dashboard with optional SMS updates for constrained environments.

- **Cross-Portal Workflow (Mock Integration)**  
  Simulated integration with CPGRAMS, municipal portals, and consumer forums.

---

## 🛠️ Tech Stack

### Frontend
- Streamlit – Interactive dashboard, voice input, complaint submission, status tracking

### AI / ML (AWS Services)
- AWS Transcribe → Speech-to-Text for regional languages  
- AWS Comprehend → Complaint classification & categorization  
- AWS SageMaker → Template optimization & continuous learning loop  
- AWS Translate (Optional) → Multilingual translation support  

### Database / Storage
- AWS S3 → Storage for audio recordings, evidence images, and complaint drafts  
- SQLite → Local database for prototype/demo execution  

### Notifications / Alerts
- AWS SNS → SMS updates & low-bandwidth alerts  
- Streamlit Dashboard → Real-time tracking visualization  

### Portal Integration / Workflow
- Mock APIs → CPGRAMS & municipal portal simulation  
- AWS Lambda → Background automation & workflow orchestration  

### Dev / Deployment (Prototype)
- Streamlit Cloud or Local Machine → Demo hosting  
- AWS Free Tier → S3, Lambda, SageMaker, SNS usage
---

## 👥 Target Users

### Citizens
- Rural and semi-urban residents with limited access to digital services  
- Low-literacy or non-English-speaking individuals  
- First-time complainants unfamiliar with formal complaint procedures  
- Elderly users or individuals uncomfortable with complex online portals  

### Government & Institutions
- Municipal departments handling civic grievances  
- State and central grievance redressal bodies  
- Public service departments seeking structured complaint intake  
- Civic-tech organizations working on governance transparency

---

## 📈 Expected Impact

- **Increased complaint acceptance rates** through standardized and properly formatted submissions  
- **Reduced rejection rates** caused by incomplete information or incorrect categorization  
- **Greater accessibility** for rural, low-literacy, and non-English-speaking citizens  
- **Faster complaint routing** to appropriate authorities  
- **Improved transparency** in grievance tracking and resolution  
- **Enhanced public trust** between citizens and government institutions

---
