# ai-voice-assistant-doctor
ai-voice-assistant-doctor
AuraDx Lab 🩺
AuraDx Lab is a Multimodal Clinical Decision Support Platform built with Python and Gradio. It is designed to assist medical evaluations by processing various inputs like medical scans (DICOM, X-rays, CT/MRI), clinical photos, pathology reports, and audio dictations using advanced AI models (Google Gemini and Groq Whisper).

Built by Lakshya & Lave

Features ✨
Multimodal Ingestion: Upload medical images (DICOM, PNG, JPG), clinical videos, laboratory reports (PDF, CSV, Excel, TXT), or record your voice directly.

Specialist AI Sub-agents: Automatically routes clinical cases to dedicated specialized medical domains (Oncology, Thoracic/Pulmonary, Dermatology, Neurology, Abdominal/Renal, and Musculoskeletal).

Deterministic Nephrology Engine: Includes built-in calculations for KDIGO 2024 kidney staging, AKI staging, and Fresenius Dialysis parameters.

Safety & Regulatory Protocols:Incorporates pre-inference safety gating for contrast/NSF risks and European Union (EU) regulatory compliance notices.

Multilingual Text & Voice:Supports multiple languages ​​( English, German, Spanish, Arabic, and Hindi ) with automated speech transcription and localized doctor voice briefings (via gTTS).

Tech Stack 🛠️
Python (Core application logic)

Gradio (Web UI interface)

Google GenAI SDK ( gemini-3.5-flash)(Multimodal clinical diagnostic engine)

OpenAI / Groq API ( whisper-large-v3) (Audio transcription)

Pydantic (Data validation & FHIR-aligned schemas)

Pandas & PyPDF / PyPDFium2 (Report and data processing)

OpenCV & Pydicom(Medical image and DICOM rendering)
