#  AI Resume Screening & Ranking System

 This project is developed as part of **Future Interns – Machine Learning Task 3 (2026)**.

##  Project Overview
This system automatically analyzes and ranks resumes based on a given job description using Natural Language Processing (NLP) techniques.

##  Key Features
- ✅ Resume text preprocessing
- ✅ Skill extraction from resumes
- ✅ Job description matching
- ✅ TF-IDF vectorization
- ✅ Cosine similarity scoring
- ✅ Candidate ranking system
- ✅ Skill gap analysis

##  How It Works
1. Load resume dataset
2. Clean and preprocess text
3. Extract skills from resumes
4. Convert text into vectors using TF-IDF
5. Compare resumes with job description using cosine similarity
6. Rank candidates based on match score
7. Identify missing skills for each candidate

##  Technologies Used
- Python 
- Pandas
- Scikit-learn
- NLTK

## output
<img width="972" height="640" alt="Screenshot 2026-04-05 105924" src="https://github.com/user-attachments/assets/c71c7a5d-e038-4c2c-8f05-348f93712e19" />


##  Dataset
- Resume Dataset (Kaggle)
- Columns used:
  - `Resume_str`
  - `Category`

## Future Improvements
- Add Streamlit UI
- Support PDF resume upload
- Use advanced NLP (spaCy / BERT)
- Deploy as web app


##  How to Run

```bash
pip install -r requirements.txt
python main.py

