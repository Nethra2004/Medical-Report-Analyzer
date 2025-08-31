## Medical Report Analyzer

MediScan AI is an AI-powered web application that analyzes medical reports using multiple specialist perspectives (Cardiologist, Psychologist, Pulmonologist) and provides a final multidisciplinary diagnosis.
The system leverages **LangChain**, **Groq’s Llama 3.1 model**, and a **Flask-based web interface** with TailwindCSS for a smooth user experience.

## 🚀 Features

* 📄 **Upload medical reports** (`.txt`, `.docx`, `.pdf`)
* 🩺 **Specialist agents** simulate reports from:

  * Cardiologist
  * Psychologist
  * Pulmonologist
* 👨‍⚕️ **Multidisciplinary team agent** consolidates findings
* 📊 **Final Diagnosis** presented as bullet points with reasoning
* 💾 Results saved automatically to `results/final_diagnosis.txt`
* 🌐 Simple **Flask + TailwindCSS web UI**
  
## 🛠️ Tech Stack

* **Backend**: Flask
* **Frontend**: TailwindCSS
* **AI/LLM**: LangChain + Groq Llama 3.1 (`llama-3.1-8b-instant`)
* **File Handling**: PyPDF2, python-docx
* **Async Execution**: ThreadPoolExecutor
