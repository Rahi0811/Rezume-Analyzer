# Resume-Analyzer
# NeuralHire

An AI-powered resume screening tool that matches candidate resumes with job descriptions using Google's Gemini API.

## Features

* Upload multiple PDF resumes
* Paste a job description
* AI-based resume evaluation
* Match score generation
* Candidate ranking
* Strength and skill-gap analysis
* Shortlist / Backup / Reject recommendations

## Tech Stack

**Frontend**

* HTML
* CSS
* JavaScript

**Backend**

* Python
* Streamlit

**AI**

* Gemini 2.5 Flash

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/neuralhire.git
cd neuralhire
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

Run the application:

```bash
streamlit run app.py
```

## Project Structure

```bash
├── app.py
├── resume-analyzer.html
├── requirements.txt
└── README.md
```

## Usage

1. Enter a job description.
2. Upload one or more PDF resumes.
3. Click **Run AI Screening Engine**.
4. Review candidate scores, strengths, gaps, and recommendations.

## Team

Built as a hackathon project to simplify and automate resume screening using AI.
