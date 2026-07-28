# 🤖 AI Resume Ranker

An AI-powered Resume Ranking System built using **Python, Flask, NLP, and Machine Learning**. This application analyzes multiple resumes, compares them with a Job Description, ranks candidates based on similarity, extracts important candidate information, and generates a downloadable ranking report.

---
## 🌐 Live Demo

🚀https://ai-resume-ranker-7vsi.onrender.com/
## 🚀 Features

- Upload multiple PDF resumes
- Enter any Job Description
- Automatic resume ranking
- Candidate name extraction
- Email extraction
- Phone number extraction
- Skill matching
- Missing skill detection
- Resume recommendation (Excellent / Good / Average / Poor)
- Download ranking report as CSV
- Clean and responsive Flask web interface

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- SpaCy
- Pandas
- PyMuPDF
- HTML
- CSS

---

## 📂 Project Structure

```
AI-Resume-Ranker/
│
├── app.py
├── utils.py
├── requirements.txt
├── skills.txt
│
├── templates/
│   ├── index.html
│   └── results.html
│
├── static/
│   └── style.css
│
├── uploads/
├── reports/
│   └── resume_ranking.csv
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Resume-Ranker.git
```

Move into project folder

```bash
cd AI-Resume-Ranker
```

Install dependencies

```bash
pip install -r requirements.txt
```

Download SpaCy model

```bash
python -m spacy download en_core_web_sm
```

Run the application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 📌 How It Works

1. Upload one or more PDF resumes.
2. Paste the Job Description.
3. The application extracts resume text.
4. Candidate details are extracted automatically.
5. Resume content is compared with the Job Description using TF-IDF and Cosine Similarity.
6. Skills are matched.
7. Candidates are ranked by similarity score.
8. Download the ranking report as CSV.

---

## 📊 Output

Each candidate receives:

- Rank
- Name
- Email
- Phone Number
- Resume Score
- Matched Skills
- Missing Skills
- Recommendation

---

## 📸 Screenshots

Add screenshots inside a **screenshots/** folder.

Example:

```
screenshots/
    home.png
    results.png
```

---

## 🎯 Future Improvements

- Support DOCX resumes
- AI-based resume feedback
- Resume keyword suggestions
- Job description optimization
- PDF report generation
- Dashboard with analytics

---

## 👨‍💻 Author

**KURAKULA SAI MANOJ**

AI & Machine Learning Internship Project

---

