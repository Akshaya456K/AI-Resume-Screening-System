#  AI Resume Screening System

An AI-powered recruitment support application designed to help recruiters evaluate, screen, and rank job candidates based on their relevance to job descriptions and requirements.

Built using **Python** and **Streamlit**, this project provides an interactive interface for resume screening, candidate ranking, and recruitment analytics.

---

##  Overview

Recruiters often need to review a large number of resumes for a single job opening. This project aims to simplify that process by providing a structured AI-assisted workflow for candidate screening.

The system allows users to:

* View recruitment statistics through an interactive dashboard
* Enter job descriptions and candidate requirements
* Upload multiple candidate resumes
* Prepare resumes for AI-based screening
* Rank candidates based on relevance and matching scores
* Analyze screening and candidate-matching results

> This system is intended as a recruitment decision-support tool. Final hiring decisions should always involve human review.

---

##  Features

###  Dashboard

The dashboard provides an overview of the recruitment system, including:

* Total jobs
* Total candidates
* Total applications
* AI engine status

###  Resume Screening

Users can:

* Enter job descriptions and requirements
* Upload multiple resumes
* Support PDF, DOCX, and TXT resume formats
* Prepare candidates for AI-based screening

###  Candidate Ranking

The system is designed to rank candidates based on AI-generated relevance or matching scores.

Potential ranking factors include:

* Skills matching
* Job description relevance
* Candidate experience
* Resume content similarity

###  Analytics

The analytics section provides insights into the screening process, including:

* Average candidate match score
* Number of highly relevant candidates
* Number of candidates screened
* Candidate ranking insights
* Recruitment screening metrics

---

##  Technologies Used

* Python
* Streamlit
* Artificial Intelligence Concepts
* Natural Language Processing (NLP)
* Machine Learning Concepts
* CSV-based Data Processing

---

##  Project Structure

```text
AI-Resume-Screening-System/
│
├── app.py
├── README.md
├── requirements.txt
│
├── data/
│   ├── resumes.csv
│   ├── jobs.csv
│   ├── applications.csv
│   └── master_resume_screening_dataset.csv
│
├── results/
│   ├── resume_screening_results.csv
│   └── final_resume_screening_results.csv
│
├── reports/
│   └── Project1_report.docx
│
└── notebooks/
    └── resume_screening.ipynb
```

---

##  Dataset Description

### `resumes.csv`

Contains candidate resume information used for screening and analysis.

### `jobs.csv`

Contains job descriptions and job-related information.

### `applications.csv`

Contains candidate application information.

### `master_resume_screening_dataset.csv`

Contains the combined dataset used for resume screening and analysis.

### `resume_screening_results.csv`

Contains generated resume screening and matching results.

### `final_resume_screening_results.csv`

Contains the final processed candidate screening and ranking results.

---

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Resume-Screening-System.git
```

### 2. Navigate to the project directory

```bash
cd AI-Resume-Screening-System
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

##  Running the Application

Run the following command:

```bash
streamlit run app.py
```

Alternatively:

```bash
python -m streamlit run app.py
```

After running the command, Streamlit will start a local server and open the application in your browser.

---

##  Application Pages

### Dashboard

Provides an overview of the AI-powered recruitment platform.

### Screen Resumes

Allows recruiters to enter job requirements and upload candidate resumes.

### Candidate Ranking

Displays candidates ranked according to their screening and matching scores.

### Analytics

Provides recruitment insights and screening performance metrics.

---

##  Future Improvements

Possible future enhancements include:

* Resume text extraction from PDF and DOCX files
* Advanced NLP-based resume parsing
* TF-IDF-based candidate matching
* Embedding-based semantic similarity
* Automated candidate scoring
* Real-time candidate ranking
* Interactive charts and visual analytics
* Database integration
* Recruiter authentication
* Explainable AI-based ranking
* Bias detection and fairness analysis

---

##  Important Note

AI-generated candidate rankings should not be used as the sole basis for hiring decisions.

The system is designed to support recruiters by reducing manual effort and organizing candidate information. Human evaluation should remain an essential part of the recruitment process.

---

##  Author

Developed as an **AI Resume Screening System** project using Python and Streamlit.

---

##  Support

If you find this project useful, consider giving the repository on GitHub!
