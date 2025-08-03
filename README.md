# Real-time-stock-market-dashboard
Resume Parser using Python, SpaCy, and PDFMiner
This project extracts useful information from resumes in PDF format. It uses:

PDFMiner for extracting text from PDF
SpaCy for NLP tasks like name extraction
Regex for extracting phone numbers, emails, skills, and education
Features
Extract name using SpaCy matcher
Extract contact number and email using regex
Match skills from a predefined list
Extract education degrees
Usage
Install dependencies:
pip install -r requirements.txt
python -m spacy download en_core_web_sm
Replace resume_paths in the script with your resume file path.

Run the script:

python resume_parser.py
File Structure
resume_parser.py: Main script
requirements.txt: Required Python packages
README.md: Project info
