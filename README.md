# 🩺 MediAid: Autonomous Medication Management System for Elderly People

**MediAid** is an **AI-powered Streamlit application** designed to help elderly individuals manage their medications independently and reliably. It supports OCR-based prescription scanning, multilingual translation, AI-powered query response, voice instructions, reminders, and real-time caregiver notifications.

---

## 🔍 **Features**

- 📄 **OCR from Prescriptions**  
  Upload prescription images or PDFs and extract content using **Tesseract OCR**.

- 🌐 **Multilingual Translation**  
  Supports translation to **English**, **Spanish**, and **Malayalam** using **Google Translate API**.

- 🔊 **Text-to-Speech (TTS)**  
  Converts translated text into audio using **gTTS**, making it easier for visually impaired users.

- 💬 **AI Chat Support**  
  Ask questions about your prescription. The system uses **LangChain** and **Google Generative AI** to provide contextual answers.

- ⏰ **Medication Reminders**  
  Set medication schedules. The system plays an alert and speaks out the reminder when it's time.

- 📱 **Caregiver Notifications**  
  If the user doesn't confirm a reminder, the app sends **SMS via Twilio** and **emails** to registered caregivers.

---

## ⚙️ **Tech Stack**

| **Component**    | **Technology/Library**                     |
|------------------|--------------------------------------------|
| Frontend         | **Streamlit**                              |
| OCR              | **PyTesseract**, **Pillow**                |
| Translation      | **Google Translate API**, **Deep Translator** |
| Text-to-Speech   | **gTTS**, **playsound**                    |
| AI & NLP         | **LangChain**, **Google Generative AI**    |
| Scheduling       | **schedule**, **datetime**, **threading**  |
| Notifications    | **Twilio SMS**, **SMTP Email**             |
| Vector Storage   | **FAISS**, **ChromaDB**                    |
| Language Support | **English**, **Spanish**, **Malayalam**    |
