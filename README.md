🩺 MediAid: Autonomous Medication Management System for Elderly People
MediAid is an AI-powered Streamlit application designed to help elderly individuals manage their medications with ease. It extracts text from medical prescriptions (images or PDFs), translates them into multiple languages, answers medication-related queries, provides audio playback, sets reminders, and alerts caregivers if doses are missed.

🔍 Features
📄 OCR from Prescriptions
Upload a scanned image or PDF of your medical prescription and extract its contents automatically using Tesseract OCR.

🌐 Multilingual Translation
Translate prescription text into English, Spanish, or Malayalam using Google Translate API for better accessibility.

🔊 Text-to-Speech (TTS)
Converts translated text into speech using gTTS and plays it aloud for users with visual impairments or literacy challenges.

💬 AI Chat Support
Ask any question related to your prescription. MediAid uses LangChain and Google Generative AI to generate intelligent responses based on prescription context.

⏰ Medication Reminders
Set and manage medication times. The system reminds users via on-screen alerts and audio prompts.

📱 Caregiver Notifications
If a dose is missed, MediAid sends real-time SMS (via Twilio) and email alerts to caregivers.
