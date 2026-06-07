# HireMind AI – Intelligent Recruitment and Interview System

## 📌 Overview

HireMind AI is an AI-powered recruitment platform designed to automate the hiring process. The system analyzes resumes, calculates ATS (Applicant Tracking System) scores, ranks candidates, conducts AI-based interviews, generates reports, and provides an admin dashboard for candidate management.

The platform helps recruiters save time by automatically screening resumes and identifying the most suitable candidates.

---

## 🚀 Features

### 👤 User Features

* User Registration and Login
* Secure Password Reset via Email
* Resume Upload
* Resume ATS Score Analysis
* AI-Based Interview Simulator
* Interview Result Tracking
* PDF Report Generation

### 👨‍💼 Admin Features

* Admin Dashboard
* View All Candidates
* ATS Score Monitoring
* Candidate Selection/Rejection
* Download Selected Candidate Reports
* User Management
* Interview Performance Monitoring

---

## 🤖 AI Features

### Resume Analysis

The system analyzes uploaded resumes and:

* Extracts text from resumes
* Detects technical skills
* Identifies projects
* Evaluates education details
* Calculates ATS score
* Ranks candidates

### Interview Simulator

The AI interview module:

* Generates interview questions
* Records answers
* Evaluates responses
* Stores interview scores
* Provides interview performance analysis

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Python
* Flask

### Database

* SQLite

### AI / NLP

* Natural Language Processing
* Resume Parsing
* Skill Extraction
* ATS Scoring Algorithm

### Additional Libraries

* Flask-Mail
* Werkzeug
* PDF Processing Libraries
* ZipFile
* SQLite3

---

## 📂 Project Structure

```text
HireMind-AI/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── uploads/
│   ├── assets/
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── admin_dashboard.html
│   ├── interview.html
│
├── app.py
├── database.db
├── requirements.txt
├── README.md
│
└── exports/
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/HireMind-AI.git

cd HireMind-AI
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

The application will start at:

```text
http://127.0.0.1:8080
```

---

## 📊 ATS Scoring Criteria

The ATS score is calculated based on:

| Criteria   | Weight |
| ---------- | ------ |
| Skills     | 40%    |
| Projects   | 20%    |
| Experience | 20%    |
| Education  | 20%    |

Maximum ATS Score: 100

---

## 🔒 Security Features

* Password Hashing
* Session Management
* Email Verification
* Password Reset Tokens
* Secure Authentication

---

## 📈 Future Enhancements

* Machine Learning Candidate Ranking
* Resume-Job Description Matching
* Real-Time Interview Evaluation
* Email Notifications
* MySQL Database Integration
* Cloud Deployment
* Advanced Analytics Dashboard
* AI Feedback Generation

---

## 🎯 Problem Statement

Organizations receive hundreds of resumes for a single job opening. Manually screening candidates is time-consuming and inefficient.

HireMind AI automates:

* Resume Screening
* Candidate Ranking
* Interview Evaluation
* Report Generation
* Candidate Management

This significantly reduces recruitment time and improves hiring efficiency.

---

## 👨‍💻 Author

**Vishal Desai**

* SQL Competition Winner
* UI/UX Design Competition Winner
* Research Paper Author
* Developer of HireMind AI

---

## 📜 License

This project is developed for educational and academic purposes.
