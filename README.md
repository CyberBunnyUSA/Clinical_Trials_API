# Clinical_Trials_API
GitHub repository script for a Data Science &amp; Machine Learning API Dashboard that pulls data from ClinicalTrials.gov and performs statistical analysis. This project includes:  A FastAPI backend  Integration with ClinicalTrials.gov API  Data wrangling & statistical analysis (Pandas, SciPy, Scikit-learn)  Visualization in a dashboard (Plotly Dash)
# Clinical Trials Data Science & ML API Dashboard

This repository provides a machine learning-powered API and interactive dashboard for analyzing clinical trials data sourced from [ClinicalTrials.gov](https://clinicaltrials.gov/).

## 🔍 Features

- Fetch & parse data from ClinicalTrials.gov API
- Statistical summaries (trial phases, recruitment status, study types)
- ML clustering of studies (based on text embedding)
- Time series and distribution plots
- REST API built with FastAPI
- Interactive dashboard built with Dash/Plotly

## 🧰 Tech Stack

- Python 3.10+
- FastAPI
- Pandas, NumPy, Scikit-learn
- Plotly Dash
- Uvicorn
- Requests
- SQLite (for local caching)

## 🚀 Quickstart

```bash
git clone https://github.com/yourusername/clinicaltrials-api-dashboard.git
cd clinicaltrials-api-dashboard
pip install -r requirements.txt
uvicorn app.main:app --reload  # Starts the FastAPI API
python app/dashboard.py        # Starts the Dash dashboard
