# Intelligent_Resume_Ranker
Overview

The Intelligent Resume Ranker is an AI-powered web application that automatically ranks candidate resumes based on their relevance to a job description. It helps recruiters quickly identify the most suitable candidates by using Natural Language Processing (NLP) and semantic similarity techniques.

The system extracts important information from uploaded resumes and compares them with the job description using SBERT (Sentence-BERT) embeddings to calculate similarity scores. Candidates are then ranked based on how well their resumes match the job requirements.

Key Features

Upload multiple resumes for analysis

Upload or paste job descriptions

Automatic resume parsing

Semantic similarity ranking using SBERT

Candidate ranking based on relevance score

Web-based dashboard interface

Fast and scalable filtering for recruitment workflows

Tech Stack

Frontend

HTML

CSS

JavaScript

Backend

Python (Flask)

Machine Learning / NLP

Sentence-BERT (SBERT)

Sentence Transformers

Cosine Similarity

Other Tools

Git

GitHub

Project Architecture

User Uploads Resume & Job Description
↓
Resume Text Extraction
↓
Text Preprocessing
↓
SBERT Embedding Generation
↓
Similarity Calculation
↓
Resume Ranking
↓
Results Displayed on Dashboard

Folder Structure
Intelligent_Resume_Ranker
│
├── SBERT_Model  # Trained model files
├── static    # CSS, JS, assets
├── templates   # HTML templates
├── uploads  # Uploaded resumes
├── web_application   # Web logic
├── app.py   # Flask application entry point
├── README.md  # Project documentation
└── .gitignore   # Ignored files


How the Ranking Works

The job description is converted into a vector embedding using SBERT.

Each resume is parsed and converted into embeddings.

Cosine similarity is calculated between the resume and job description.

Resumes are ranked from highest similarity score to lowest.

The dashboard displays the ranked candidates.

Installation & Setup
Clone the repository
git clone https://github.com/Srushti-K-03/resume-rank-ai.git
Navigate to the project directory
cd resume-rank-ai
Install dependencies
pip install -r requirements.txt
Run the application
python app.py
Open in browser
http://localhost:5000

Example Use Case

Recruiters can upload a job description and multiple resumes.
The system automatically analyzes each resume and ranks candidates based on semantic relevance, helping recruiters shortlist candidates faster.

Future Improvements

Automatic skill extraction

Resume summarization

Candidate profile scoring

Integration with job portals

Support for DOCX and PDF parsing improvements


## Screenshots
### HR Dashboard
<img width="1919" height="1038" alt="Screenshot 2026-01-02 185258" src="https://github.com/user-attachments/assets/9f5ae395-c798-4c85-8731-fc4a46068215" />

### Job Description & Performance
<img width="1170" height="791" alt="Screenshot 2026-01-09 182234" src="https://github.com/user-attachments/assets/bb74e11d-a4fd-40e8-bfd6-3c2ef08b8d57" />

### AI Candidate Ranking
<img width="581" height="666" alt="Screenshot 2026-01-09 182509" src="https://github.com/user-attachments/assets/1fc66874-100d-46a9-81e7-931c4cdfcb4a" />
<img width="405" height="726" alt="Screenshot 2026-01-09 182416" src="https://github.com/user-attachments/assets/45527c3e-6824-47d2-9282-948f5124f01d" />


### Candidate Pipeline

<img width="1525" height="685" alt="Screenshot 2026-01-09 185204" src="https://github.com/user-attachments/assets/2787e15c-7aa0-43c5-95e9-6554aa62a435" />
