# Resume-Analyzer
# NeuralHire - AI Resume-to-Job Fit Analyzer

## Problem Statement

### AI for Employability

Students and job seekers often struggle to understand how well their skills and experience align with job requirements. Recruiters, on the other hand, spend significant time manually reviewing resumes and identifying suitable candidates.

Traditional resume screening methods rely heavily on keyword matching and manual evaluation, making the process slow, inconsistent, and inefficient.

This project addresses the problem statement:

> **"Build an AI tool that helps students become job-ready through resume analysis, interview evaluation, skill-gap planning, portfolio review, or job-posting trust checks."**

Specifically, NeuralHire focuses on:

> **AI Resume-to-Job Fit Analysis with Skill-Gap Reporting**

---

## Solution Overview

NeuralHire is an AI-powered platform that evaluates candidate resumes against a given job description using Google's Gemini API.

The system:

* Accepts a job description from recruiters or students.
* Processes multiple PDF resumes.
* Extracts resume content automatically.
* Performs semantic matching between resumes and job requirements.
* Generates a compatibility score.
* Identifies candidate strengths.
* Highlights missing skills and improvement areas.
* Provides an AI-generated recommendation:

  * Shortlist
  * Backup
  * Reject

This helps recruiters screen candidates faster and enables students to understand where they need improvement to become job-ready.

---

## API Used

### Google Gemini 2.5 Flash API

Used for:

* Resume analysis
* Semantic matching
* Candidate scoring
* Skill-gap detection
* Experience evaluation
* Recommendation generation

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Streamlit

### Libraries

* PyPDF2
* Pandas
* Google GenAI SDK

### AI Model

* Gemini 2.5 Flash

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/neuralhire.git
cd neuralhire
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Gemini API Key

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your_api_key_here
```

### 4. Run the Application

```bash
streamlit run app.py
```

The application will start locally on:

```text
http://localhost:8501
```

---

## Demo Instructions

### Step 1

Paste a Job Description into the input field.

### Step 2

Upload one or more PDF resumes.

### Step 3

Click **Run AI Screening Engine**.

### Step 4

Review the generated results:

* Match Score
* Candidate Ranking
* Key Strengths
* Skill Gaps
* Experience Alignment
* Final Recommendation

---

## Future Improvements

* Personalized learning roadmap for students
* Resume optimization suggestions
* ATS compatibility checking
* Interview question generation
* Portfolio analysis integration
* LinkedIn profile evaluation

---

## Team

Developed as part of a Hackathon project under the **AI for Employability** theme.

