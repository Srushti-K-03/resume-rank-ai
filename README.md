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
