# 💊 AI Medication Explainer

An AI-powered healthcare application that helps patients understand handwritten prescriptions by providing simplified medicine explanations, multilingual support, voice assistance, and drug interaction alerts.

---

## 📖 Overview

Understanding handwritten prescriptions can be difficult for many patients due to complex medical terminology, language barriers, and unclear dosage instructions. This project addresses these challenges by extracting medicine information from prescription images and converting it into easy-to-understand explanations.

The application uses OCR to extract medicine details, retrieves authentic drug information from OpenFDA, generates patient-friendly explanations using a Large Language Model (LLM), translates the explanation into multiple languages, converts it into speech, and checks for potential drug interactions.

---

## ✨ Features

- 📷 Upload handwritten or printed prescription images
- 🔍 Extract medicine details using PaddleOCR
- 💊 Identify medicine name, strength, dosage, duration, and food instructions
- 🌐 Retrieve authentic medicine information using OpenFDA
- 🤖 Generate AI-powered patient-friendly medicine explanations
- 🌍 Multilingual support (English, Telugu, Hindi, Kannada, Tamil)
- 🔊 Text-to-Speech for medicine explanations
- ⚠️ Detect possible drug interactions and display severity
- 💻 Interactive React-based web interface

---

## 🛠️ Tech Stack

### Frontend
- React
- Axios
- React Markdown

### Backend
- FastAPI
- Python

### OCR
- PaddleOCR

### AI Model
- OpenRouter GPT-OSS

### Drug Database
- OpenFDA API

### Translation
- Google Translator

### Text-to-Speech
- gTTS (Google Text-to-Speech)

---

## 🏗️ System Architecture

```
Prescription Image
        │
        ▼
PaddleOCR
        │
        ▼
Medicine Extraction
        │
        ▼
OpenFDA API
        │
        ▼
OpenRouter LLM
        │
        ▼
Translation
        │
        ▼
Drug Interaction Detection
        │
        ▼
Text-to-Speech
        │
        ▼
React Frontend
```

---

## ⚙️ Workflow

1. User uploads a prescription image.
2. PaddleOCR extracts text from the prescription.
3. Medicine details such as name, dosage, strength, and duration are identified.
4. OpenFDA retrieves authentic medicine information.
5. The OpenRouter LLM generates patient-friendly explanations.
6. The explanation is translated into the selected language.
7. Drug interactions are analyzed.
8. The explanation is converted into speech.
9. Results are displayed in the React web application.

---

## 📂 Project Structure

```
AI-Medication-Explainer
│
├── backend
│   ├── routes
│   ├── services
│   ├── parser
│   ├── interactions
│   └── main.py
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── screenshots
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Medication-Explainer.git

cd AI-Medication-Explainer
```

---

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload
```

---

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```
OPENROUTER_API_KEY=your_api_key_here
```

---

## 📸 Screenshots

### Home Page

*(Add Screenshot Here)*

---

### Upload Prescription

*(Add Screenshot Here)*

---

### AI Explanation

*(Add Screenshot Here)*

---

### Drug Interaction Detection

*(Add Screenshot Here)*

---

### Voice Assistance

*(Add Screenshot Here)*

---

## 🎯 Current Features

- ✅ OCR-based prescription reading
- ✅ Medicine extraction
- ✅ OpenFDA integration
- ✅ AI-generated medicine explanations
- ✅ Multilingual support
- ✅ Text-to-Speech
- ✅ Drug interaction detection
- ✅ React user interface

---

## 🔮 Future Enhancements

- Mobile application
- Reminder scheduler
- Better OCR accuracy
- Deployment to cloud
- Improved UI/UX
- Expanded multilingual support
- Larger prescription dataset testing

---

## 🎓 Academic Information

**Project Title:** AI Medication Explainer

**Department:** Computer Science and Engineering

**Institution:** Dayananda Sagar University

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Yarragunta Aaslesha**

Computer Science and Engineering

Dayananda Sagar University

GitHub: https://github.com/yourusername
