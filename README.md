# AI-Resume-Job-Description-Matche
A Python and Streamlit project that compares resume text with a job description and builds a reusable prompt for structured, evidence-based feedback


Features


Paste resume and job-description text

Basic keyword-overlap analysis

View shared and job-only keywords

Generate and download a prompt for deeper review

Guardrails against invented experience and automated hiring decisions


Tech Stack

Python, Streamlit, regular expressions, prompt engineering.


Setup

pip install -r requirements.txt
streamlit run app.py

Limitations

The keyword comparison is a simple text-overlap heuristic, not an ATS score or hiring recommendation. This version does not call an external AI API. Avoid entering sensitive personal information into tools you do not trust.


Future Improvements


Optional LLM API integration

PDF/DOCX text extraction

Export feedback reports

Prompt evaluation tests
