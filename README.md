# ATS Resume Parser
An AI-powered Applicant Tracking System (ATS) tool built with Python, Streamlit, and Google Gemini API that analyzes resumes against job descriptions to provide professional feedback, highlight missing skills, and calculate a match percentage.

---

## Features
  - 📄 Resume Upload: Upload resumes in PDF format.
  - 🧠 AI Evaluation: Uses Google Gemini to review resumes based on the job description.
  - 📊 ATS Match Percentage: Calculates how well the resume matches the job requirements.
  - 🔍 Skill Gap Analysis: Lists missing keywords or skills.
  - 💡 HR-Style Feedback: Provides strengths and weaknesses for improvement.
  
---

## Tech Stack
  - Python 3
  - Streamlit – for interactive web UI
  - pdf2image – for PDF to image conversion
  - Pillow (PIL) – image handling
  - Google Generative AI (Gemini API) – for AI-based evaluation
  - dotenv – to manage API keys securely

---

## How It Works
  1. Enter a job description in the text box.
  2. Upload a PDF resume.
  3. Choose one of the analysis options:
      - Tell Me About the Resume → HR-style feedback
      - Percentage Match → ATS score + missing keywords + recommendations
  4. View results directly in your browser.

---

## Example Output
  - Percentage Match: 78%
  - Missing Keywords: Python, SQL, Cloud Computing
  - Final Thoughts: Strong background in data analysis, but lacks cloud-based project experience.
  
---

## ScreenShots
![image alt](https://github.com/Jatinkumarpanwar/ATS-Resume-Parser/blob/main/Screenshot%202025-08-14%20112309.png)
