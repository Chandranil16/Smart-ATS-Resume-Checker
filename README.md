# 🧠 Smart-ATS-Resume-Checker

A smart, AI-powered ATS (Applicant Tracking System) Resume Analyzer built using **Python**, **gemini-2.5-flash LLM**, and **Streamlit**. This tool helps job applicants optimize their resumes by comparing them with job descriptions and providing actionable feedback to increase their chances of passing ATS filters used by employers.

---

## 🚀 Features

✅ **Resume Upload & Job Description Input**  
Users can upload their resumes and paste the job description of their target role.

✅ **ATS Score Calculation**  
Automatically calculates the **percentage match** between the resume and job description.

✅ **Missing Keywords & Skills Detection**  
Identifies **missing skills**, **keywords**, and **important sections** the resume lacks.

✅ **Improvement Suggestions**  
Gives suggestions to **improve resume content** to better match the job posting.

✅ **Interactive Q&A**  
Users can ask follow-up questions on how to further **optimize** or **tailor** their resume for a specific job.

✅ **LLM-Powered Insight**  
Powered by **gemini-2.5-flash**, providing intelligent analysis and natural language feedback.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for the user interface
- **gemini-2.5-flash** – for LLM-based resume analysis using Google AI Studio through GCP console
- **pypdf** – PDF/Text Parsing Libraries

---

## 💡 How It Works

1. The user uploads their resume (PDF format).
2. The user pastes the relevant job description into a text box.
3. The app:
   - Extracts and analyzes text from the resume.
   - Compares it with the job description.
   - Calculates an **ATS match score**.
   - Highlights missing keywords and required skills.
   - Provides **custom suggestions** to enhance the resume.
4. The user can interact with the app to ask follow-up questions.

---


