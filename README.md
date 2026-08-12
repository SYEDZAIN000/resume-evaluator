# AI Resume Evaluator

An AI-powered Resume Evaluator that analyzes resumes against a Job Description and generates structured candidate evaluations using an LLM.

## 🚀 Features

- 📄 Supports PDF and DOCX resumes
- 🧠 Uses an LLM to analyze candidate profiles
- 🎯 Compares candidate skills against job requirements
- 📊 Generates structured evaluation results
- 🏆 Ranks candidates based on their match score
- 🔒 Uses environment variables for API credentials
- 🧩 Uses Pydantic for structured data validation

## 🛠️ Tech Stack

- Python
- Groq API
- Pydantic
- PyPDF
- python-docx
- uv
- LLM-based structured evaluation

## ⚙️ How It Works

```text
Job Description
       ↓
Resume Parsing
       ↓
Candidate Information Extraction
       ↓
LLM Evaluation
       ↓
Skill & Requirement Matching
       ↓
Candidate Scoring
       ↓
Candidate Ranking
```
## 📂 Project Structure
```
resume-evaluator/
│
├── main.py
├── resume_evaluator.py
├── pyproject.toml
├── uv.lock
├── .python-version
├── .gitignore
└── README.md
```

##🔑 Environment Setup

Create a .env file in the project directory:
```
GROQ_API_KEY=your_api_key_here
```

##▶️ Run the Project
Install the dependencies using uv and run:
```
uv run main.py
```
## 📌 Learning Project

This project was built as part of my AI Engineering learning journey.

The goal was to understand practical implementation of:

- LLM APIs
- Prompt engineering
- Structured outputs
- Pydantic models
- Document parsing
- Resume-job matching
- AI-assisted candidate evaluation

## 🔮 Future Improvements

- Add a Streamlit web interface
- Add explainable scoring
- Add weighted required/preferred skills
- Export evaluation results to CSV
- Add automated tests
- Deploy as a web application

## 👨‍💻 Author

**Syed Zain Ahmed**
