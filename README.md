# 🎓 AI Placement Predictor & Employability Diagnostics Engine

🏆 **4th Prize Winner — National-Level Spectrum Hackathon**

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-red.svg)](https://streamlit.io/)
[![XGBoost](https://img.shields.io/badge/XGBoost-2.0%2B-green.svg)](https://xgboost.readthedocs.io/)
[![SHAP](https://img.shields.io/badge/SHAP-Explainable%20AI-orange.svg)](https://shap.readthedocs.io/)

An AI-powered employability diagnostics platform that predicts student placement readiness, explains predictions using SHAP, identifies career-specific skill gaps, generates personalized learning roadmaps, and provides institutional analytics for Training & Placement Officers (TPOs).

Developed as part of the **National-Level Spectrum Hackathon**, this project addresses the challenge of evaluating student employability beyond academic grades by combining machine learning, explainable AI, and actionable career guidance.

---

## 📌 Problem Statement

Student employability depends on multiple factors, including academic performance, programming skills, certifications, projects, internships, aptitude, communication, and extracurricular activities.

Colleges need effective ways to identify placement-ready students, diagnose skill deficiencies, recommend targeted improvements, and understand readiness across departments.

**Our solution:** A unified machine learning platform that provides student-level placement diagnostics and institution-level employability insights.

---

## 🌟 Key Features

### 1. 🎓 Student Placement Predictor

- Evaluates a comprehensive **52-feature student employability profile**.
- Covers six core pillars: Academics, Programming, Experience, Aptitude, Soft Skills, and Extracurriculars.
- Uses a hyperparameter-tuned XGBoost classification engine.
- Predicts student placement readiness.
- Saves new student entries with unique student IDs beginning with `STU1001`.
- Helps maintain student records while avoiding duplicate department registrations.

### 2. 🔍 Explainable AI with SHAP

- Uses **SHAP TreeExplainer** to explain individual predictions.
- Displays positive and negative feature contributions.
- Highlights factors that influence a student's employability assessment.
- Makes model outputs more transparent and interpretable.

### 3. 🎯 Target Role Skill Gap Analyzer

Evaluates student competencies against target-role benchmarks for:

- Full Stack Developer
- Data Analyst
- DevOps Engineer
- QA Engineer

Features include:

- Career-specific skill benchmarking.
- Identification of missing or underdeveloped skills.
- Priority-based gap classifications: Critical, High, Medium, and Low.

### 4. 🗺️ Personalized Career Roadmap Generator

- Generates a tailored **four-phase learning roadmap**.
- Provides estimated completion timelines.
- Recommends relevant courses and learning activities.
- Suggests actionable practice drills to improve career readiness.

### 5. 📊 TPO Institutional Dashboard

- Multi-department employability analytics.
- Placement-readiness distribution charts.
- Department-wide skill heatmaps.
- Identification of students requiring additional support.
- Priority intervention lists to support targeted training decisions.

### 6. 🔬 Model Explainability & Analysis

- Global feature-importance visualizations.
- Model evaluation metrics.
- Feature analysis and ablation reports.
- Individual student lookup and diagnostic analysis.

---

## 🏗️ System Architecture

```text
Student Profile / Data Input
          |
          v
     Streamlit UI
          |
          v
 XGBoost Placement Predictor
       (52 Features)
          |
          v
    SHAP TreeExplainer
          |
          v
   Skill Gap Analyzer
          |
          v
 Personalized Career Roadmap
          |
          v
 Institutional TPO Dashboard
```

---

## 🔄 How It Works

1. **Student data input:** Collect academic, technical, practical, aptitude, and soft-skill information.
2. **Feature processing:** Prepare student attributes for the machine learning pipeline.
3. **Placement prediction:** Use the trained XGBoost classifier to assess placement readiness.
4. **Prediction explanation:** Apply SHAP to identify factors influencing the model's output.
5. **Skill gap analysis:** Compare competencies with target-role benchmarks.
6. **Roadmap generation:** Produce phased learning recommendations and practice activities.
7. **Institutional analytics:** Aggregate student information into department-level insights for TPOs.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web application |
| XGBoost | Placement classification model |
| SHAP | Explainable AI and feature attribution |
| Pandas | Student dataset processing |
| Scikit-learn | Preprocessing and machine learning utilities |
| Plotly / Streamlit charts | Data visualization, as implemented |
| CSV | Student dataset storage |
| Pickle | Serialized model and preprocessing artifacts |
| JSON | Model evaluation metrics |

---

## 🏆 Hackathon Achievement

**4th Prize — National-Level Spectrum Hackathon**

Participating in this hackathon provided an opportunity to address a real-world employability challenge by combining machine learning, explainability, personalized upskilling, and institutional analytics in one application.

---

## 🔮 Future Scope

- Track changes in student readiness over time.
- Expand career benchmarks and learning recommendations.
- Improve model validation using larger, representative datasets.
- Add progress tracking for personalized learning roadmaps.
- Extend institutional analytics to support training planning across departments.

---

## 👥 Project Information

- **Project:** AI Placement Predictor & Employability Diagnostics Engine
- **Domain:** Data Science / Artificial Intelligence
- **Event:** National-Level Spectrum Hackathon
- **Achievement:** 4th Prize
- **Primary Technologies:** Python, Streamlit, XGBoost, SHAP

---

*Turning employability data into explainable insights and actionable career preparation.*
