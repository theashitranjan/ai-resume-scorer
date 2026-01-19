# AI Resume Scorer 🚀

AI-powered system that scores resumes (PDF/DOC/TXT) against a job description using TF-IDF and cosine similarity. Outputs match scores (0-100).

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Features
- Extract text from PDF, DOCX, TXT
- TF-IDF vectorization + cosine similarity scoring
- Ranked output with scores
- CLI and future web API

## 🚀 Quick Start
```bash
pip install -r requirements.txt
python src/main.py --job_desc data/job.txt --resumes data/resumes/ --output scores.csv
