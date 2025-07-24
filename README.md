![CivicAI Banner](assets/civicai-banner.jpg)

#homa-bay legal hack#
# CivicAI - Multilingual Civic Education via SMS/WhatsApp

## 🧩 Problem

Over **17 million Kenyans**, especially in marginalized and rural communities, lack access to reliable, understandable information about their **rights, laws, and government services**.

### Barriers:
- 📕 Language exclusion (legal info only in English/Kiswahili)
- 📵 Low digital access (smartphones, data bundles, digital literacy)
- 😕 Mistrust/confusion over how to access services (e.g., NHIF, GBV, land rights)

**Sources:**  
KNBS 2022 Digital Access Survey,  
CIPESA Reports on Digital Exclusion,  
Kenya Law Reform Commission

---

## 💡 Solution: CivicAI

**CivicAI** is a **multilingual AI civic assistant** accessible via **SMS and WhatsApp**. It helps citizens understand **laws, rights, and public services** in their **local languages** using simple, user-friendly language.

### ✨ Key Features

- 📩 **SMS & WhatsApp Chatbot** (no smartphone app needed)  
- 🗣️ **Supports Local Languages** – Kikuyu, Kiswahili, Luo, Kalenjin, Somali, etc.  
- 🧠 **Simplifies Complex Laws** – e.g., land, ID, GBV, NHIF, Huduma  
- 🎙️ **Voice Notes & Keyword Prompts** (for low-literacy users)  
- 🔌 **Offline-First Design** – works on low-end feature phones  
- 📊 **Analytics Dashboard** – for civic trends & usage insights  

---

## 🏁 Tech Stack

| Component | Stack |
|----------|-------|
| Backend | Python (FastAPI) |
| AI Logic | LangChain + RAG Pipeline |
| Messaging | Twilio API (SMS & WhatsApp) |
| Translation | Google/Azure Translate API + Custom local tuning |
| Knowledge Retrieval | Pinecone or Weaviate (Vector DB for embeddings) |
| Fallback Logic | Airtime Plugin for default responses |

---

## 🧨 Competitor Analysis (Kenya)

| Competitor           | Gaps |
|----------------------|------|
| **Shupavu291 (Eneza)** | Focused on school education, Kiswahili-only |
| **Ushahidi**           | Crisis mapping, not civic education |
| **Huduma Kenya Portal** | Internet + literacy required, English-only |
| **Mzalendo**           | MP tracker, not interactive or multilingual |
| **Legal Aid Bot (Pilot)** | English-only, web-based, limited scope |

---

## 🟢 What Makes CivicAI Unique

- ✅ First civic AI tool fully accessible via **SMS**
- ✅ **Multilingual + voice support**
- ✅ **Offline-first** design for low-end phones
- ✅ Uses AI to **simplify** and **localize** legal info

---

## 💸 Business Model

- 🤝 **Donor-Funded Pilot Rollouts** – NGOs, legal aid orgs, civic tech funds  
- 🏛️ **Gov Partnerships** – NHIF, Judiciary, Ministry of ICT  
- 🆓 **Freemium Access** – Basic info free, premium for advanced/legal queries  
- 📊 **Civic Insights** – Sell anonymized analytics to policy makers & researchers  

---

## 🎯 Impact

- ✅ **Reduces misinformation** and confusion
- ✅ **Improves civic & legal awareness** for excluded populations
- ✅ **Promotes equity** in public service access
- ✅ **Bridges trust gap** between citizens and institutions
