# Resume-Analyzer
# 🎯 NeuralHire — AI Resume Screening & Talent Intelligence Platform

NeuralHire is an AI-powered resume screening system that helps recruiters automatically evaluate candidates against a job description using Google's Gemini 2.5 Flash model.

The platform extracts information from uploaded PDF resumes, performs semantic analysis against the provided job description, generates candidate scores, identifies strengths and skill gaps, and provides hiring recommendations.

---

## 🚀 Features

* 📄 PDF Resume Parsing
* 🤖 Gemini 2.5 Flash Powered Evaluation
* 🎯 Semantic Resume-to-JD Matching
* 📊 Candidate Match Scoring (0–100%)
* 🌟 Strength Identification
* ⚠️ Skill Gap Analysis
* 🏆 Automatic Candidate Ranking
* 📋 Hiring Verdict Generation

  * Shortlist
  * Backup
  * Reject
* 📈 Recruiter Dashboard
* 🎨 Modern Landing Page UI

---

## 🛠 Tech Stack

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Backend

* Python
* Streamlit

### AI & NLP

* Google Gemini 2.5 Flash API

### Libraries

* Streamlit
* Pandas
* PyPDF2
* Google GenAI SDK

---

## 📂 Project Structure

```bash
NeuralHire/
│
├── app.py
├── resume-analyzer.html
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/neuralhire.git
cd neuralhire
```

### 2. Create Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

Create a `requirements.txt` file:

```txt
streamlit
pandas
PyPDF2
google-genai
python-dotenv
```

Install:

```bash
pip install -r requirements.txt
```

---

## 🔑 Gemini API Setup

### Create a `.env` file

```env
GEMINI_API_KEY=YOUR_API_KEY
```

### Load the API Key

```python
from dotenv import load_dotenv
import os

load_dotenv()

API_KEY = os.getenv("GEMINI_API_KEY")
```

Initialize Gemini:

```python
client = genai.Client(api_key=API_KEY)
```

---

## ▶️ Running the Backend

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will be available at:

```txt
http://localhost:8501
```

---

## 🌐 Running the Frontend

Open:

```bash
resume-analyzer.html
```

or serve locally:

```bash
python -m http.server 8000
```

Then visit:

```txt
http://localhost:8000
```

---

## 📖 How It Works

### Step 1 — Define the Job Description

Paste a complete Job Description containing:

* Required Skills
* Experience Requirements
* Responsibilities
* Preferred Qualifications

### Step 2 — Upload Candidate Resumes

Upload one or more PDF resumes.

### Step 3 — Run AI Screening

Click:

```txt
🚀 Run AI Screening Engine
```

### Step 4 — Review Results

NeuralHire generates:

* Candidate Match Score
* Candidate Ranking
* Key Strengths
* Skill Gaps
* Experience Alignment
* Hiring Verdict

---

## 📊 Example Output

```json
{
  "candidate_name": "John Doe",
  "match_score": 87,
  "key_strengths": [
    "Python",
    "AWS",
    "REST APIs"
  ],
  "skills_gap": [
    "Docker"
  ],
  "experience_alignment": "Strong alignment with backend development requirements.",
  "verdict": "Shortlist"
}
```

---

## 🔒 Security

Never expose your API key publicly.

Add the following to `.gitignore`:

```gitignore
.env
venv/
__pycache__/
*.pyc
```

---

## 🚀 Future Enhancements

* ATS Integration
* OCR-Based Resume Parsing
* Resume Database Storage
* Multi-language Resume Support
* Recruiter Authentication
* Analytics Dashboard
* CSV & PDF Report Export
* AI Interview Question Generator

---

## 👥 Team

Built during a Hackathon to demonstrate how Generative AI can streamline recruitment workflows and improve hiring efficiency.

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider starring the repository.
