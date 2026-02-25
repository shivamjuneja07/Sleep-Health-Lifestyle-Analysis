# 😴 Sleep Health & Lifestyle Analysis
### *A Story of Patterns, Risks, and Predictive Insights*

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-6C63FF?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-FF6584?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-ML-43D9AD?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Complete-FFB830?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project delivers a **full-spectrum analytical narrative** on a Sleep Health & Lifestyle dataset of **374 individuals** across 13 health and lifestyle variables. As a business analyst, the goal was to go beyond surface-level exploration — to ask the *right* questions, apply rigorous statistical methods, and build a machine learning model capable of predicting sleep disorders from lifestyle data alone.

The analysis is structured as a **story-driven report** in Jupyter Notebook, progressing from raw data to actionable executive recommendations.

---

## 🎯 Business Questions Answered

| # | Question | Method |
|---|----------|--------|
| 1 | Who is most at risk of sleep disorders? | EDA + Occupation Risk Profiling |
| 2 | Is stress statistically linked to poor sleep? | Kruskal-Wallis Hypothesis Testing |
| 3 | Does BMI category associate with disorder type? | Chi-Square Test |
| 4 | Which occupations need targeted health interventions? | Bubble Chart Risk Matrix |
| 5 | Can we predict sleep disorders from lifestyle data? | Multi-model ML Classification |
| 6 | What are the top early warning signals? | Feature Importance Analysis |

---

## 📊 Key Findings

> **42%** of the population has a clinically relevant sleep disorder — significantly above the ~30% general population baseline.

```
🔴 Stress Level         → #1 differentiator between disorder groups (p < 0.001)
🟡 BMI + Blood Pressure → Co-predictors of Sleep Apnea risk  
🟠 Occupation           → Sales Reps & Nurses show >60% disorder rate
🟢 ML Model Accuracy    → 90%+ accuracy using lifestyle data only
```

---

## 🗂️ Project Structure

```
📦 sleep-health-analysis/
├── 📓 sleep_health_analysis.ipynb    ← Main analysis notebook
├── 📄 README.md                      ← This file
├── 📊 Sleep_health_and_lifestyle_dataset.csv
├── 📋 requirements.txt
└── 📸 figures/
    ├── fig_01_population_overview.png
    ├── fig_02_sleep_landscape.png
    ├── fig_03_occupation_risk.png
    ├── fig_04_cardiovascular_risk.png
    ├── fig_05_age_gender.png
    ├── fig_06_correlation.png
    ├── fig_07_hypothesis_tests.png
    ├── fig_08_model_evaluation.png
    └── fig_09_executive_summary.png
```

---

## 🧪 Analysis Pipeline

```
Raw Data
   │
   ▼
┌─────────────────────────────────┐
│ 1. DATA QUALITY & ENGINEERING   │
│  • Missing value audit          │
│  • Blood pressure parsing       │
│  • AHA BP classification        │
│  • Age group binning            │
│  • WHO adequate sleep flagging  │
└──────────────┬──────────────────┘
               │
               ▼
┌─────────────────────────────────┐
│ 2. EXPLORATORY DATA ANALYSIS    │
│  • Population demographics      │
│  • Sleep quality landscape      │
│  • Occupation risk profiling    │
│  • Cardiovascular risk matrix   │
└──────────────┬──────────────────┘
               │
               ▼
┌─────────────────────────────────┐
│ 3. STATISTICAL TESTING          │
│  • Pearson correlation matrix   │
│  • Kruskal-Wallis H tests       │
│  • ANOVA                        │
│  • Chi-Square association tests │
└──────────────┬──────────────────┘
               │
               ▼
┌─────────────────────────────────┐
│ 4. MACHINE LEARNING             │
│  • Logistic Regression          │
│  • Random Forest (★ Best)       │
│  • Gradient Boosting            │
│  • 5-fold Stratified CV         │
│  • Feature importance ranking   │
└──────────────┬──────────────────┘
               │
               ▼
   Executive Recommendations
```

---

## 🚀 Getting Started

### Prerequisites
```bash
git clone https://github.com/yourusername/sleep-health-analysis.git
cd sleep-health-analysis
pip install -r requirements.txt
```

### Run the notebook
```bash
jupyter notebook sleep_health_analysis.ipynb
```

> ⚠️ Make sure `Sleep_health_and_lifestyle_dataset.csv` is in the same directory as the notebook.

---

## 📦 Requirements

```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
scikit-learn>=1.2.0
scipy>=1.10.0
jupyter>=1.0.0
```

---

## 🤖 Machine Learning Results

| Model | CV Accuracy | Test Accuracy |
|-------|-------------|---------------|
| Logistic Regression | ~82% | ~82% |
| **Random Forest** | **~91%** | **~91%** |
| Gradient Boosting | ~90% | ~90% |

> Best model: **Random Forest Classifier** with 200 estimators, 5-fold stratified cross-validation

### Top 5 Predictive Features
1. **Quality of Sleep** — single strongest predictor
2. **Stress Level** — direct lifestyle driver
3. **BMI Category** — body composition proxy
4. **Systolic Blood Pressure** — cardiovascular link
5. **Occupation** — contextual lifestyle proxy

---

## 💡 Executive Recommendations

| Priority | Insight | Action |
|----------|---------|--------|
| 🔴 High | Stress is the #1 disorder driver | Deploy CBT-I programs; conduct workload audits in high-stress roles |
| 🔴 High | 42% disorder prevalence | Mandatory annual sleep health screenings across workforce |
| 🟡 Medium | Sales & Nursing have >60% disorder rate | Role-specific health policies; flexible shift management |
| 🟡 Medium | BMI + BP co-predict Sleep Apnea | Use as co-screening triggers in primary care |
| 🟢 Low | ML achieves 90%+ accuracy | Deploy as early-warning triage tool in wellness platforms |

---

## 📁 Dataset

- **Source:** [Kaggle — Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
- **Rows:** 374 | **Columns:** 13
- **Target Variable:** Sleep Disorder (None / Insomnia / Sleep Apnea)

---

## 👤 About

This project was built to demonstrate technically advanced, insight-driven business analysis — combining rigorous statistics, compelling visuals, and actionable ML predictions into a cohesive narrative.

**Skills demonstrated:** Data Wrangling · Feature Engineering · Statistical Hypothesis Testing · Machine Learning · Data Visualisation · Business Communication

---

<p align="center">
  <em>Built with 📊 data, 🧠 rigor, and ☕ coffee</em>
</p>
