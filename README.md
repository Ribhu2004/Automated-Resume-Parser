# Automated-Resume-Parser
Automated Resume Parser
# Automated Resume Parser

## Description
This system processes resume files (PDF/DOCX), extracts key candidate details (name, email, phone, skills, education) and stores them in a PostgreSQL database for search and retrieval.

## Technologies
- Python 3.x  
- Flask  
- spaCy (for NLP)  
- PDFPlumber / docx2txt (for file extraction)  
- PostgreSQL  

## Setup Instructions
1. Clone repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
