
## src/README.md

```markdown
# 🔧 Source Code

Core Python modules for the resume scoring system.

## 📁 Modules

- `__init__.py` - Package initializer
- `text_extractor.py` - PDF/DOCX/TXT → clean text
- `scorer.py` - TF-IDF vectorization + cosine similarity scoring
- `main.py` - CLI entrypoint: `python src/main.py`

## Usage
```bash
cd src
python main.py --job_desc ../data/job.txt --resumes ../data/resumes/ --output ../data/scores.csv
