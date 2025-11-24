# Health Risk Assessment AI

This project analyzes real-world style WhatsApp conversations between an AI chatbot and healthcare clients to automatically identify:
- **HIV acquisition risk**
- **Mental health disorder risk**
- **Personalized recommendations aligned with South African NDOH guidelines**

The goal of the project is to demonstrate the use of **Python + NLP** for health triage, risk detection, and decision support based on conversational data.

---

## 🔍 Problem Statement
Healthcare conversations often contain subtle indicators of risk that may be missed in manual screening.  
This notebook builds a transparent and explainable pipeline that:
1. Processes raw conversational text
2. Extracts risk-related signals from user intent, behaviour and sentiment
3. Generates HIV and mental-health risk scores
4. Outputs an actionable treatment / recommendation plan

---

## 🧠 Approach
The solution applies a combination of:
- Text preprocessing
- Keyword and symptom mapping based on clinical guidelines
- Sentiment and behavioural pattern scoring
- Weighted rule-based risk model (explainable by design)

This ensures every score can be traced back to *why* it was given — a requirement in healthcare applications.

---

## 📂 Repository Contents
| File | Description |
|------|-------------|
| `conversational-health-risk-analyzer.ipynb` | Final solution including full code + outputs |
| `data/health_ai_whatsapp_100_conversations_long.txt` | Dataset of synthetic WhatsApp health conversations |
| 

---

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/health-risk-assessment-ai.git
