---
permalink: /cv/
title: "CV"
author_profile: true
redirect_from:
  - /resume
---

<a href="/files/ASHIK_AHAMED.pdf" class="btn btn--primary" target="_blank" rel="noopener noreferrer">📄 Download Full CV (PDF)</a>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #1565c0;">
<h2 style="margin-top:0;">Education</h2>
<p><strong>B.Sc. in Computer Science and Engineering (Major: Information Systems)</strong> — American International University–Bangladesh (AIUB), Dhaka, 2021 – 2025<br>
CGPA: 3.89 / 4.00 (Dean's List – 4 times)<br>
Relevant Coursework: Machine Learning, Data Science, Probability &amp; Statistics, Data Warehousing &amp; Data Mining, Computer Vision &amp; Pattern Recognition, Artificial Intelligence &amp; Expert Systems<br>
English: IELTS Academic, Overall Band 7.0 (2026)</p>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #c62828;">
<h2 style="margin-top:0;">Publications</h2>
<p><strong>Ahamed, A.</strong> (first author), Raxit, S., Zayad, A. A., Hasan, S. I., &amp; Tabassum, N. <em>Enhancing Heatwave Prediction Using Explainable AI: Feature Selection and Model Optimization for Improved Forecasting.</em> International Conference on Frontiers in Computing and Systems (COMSYS 2025). Accepted, to appear in proceedings (Springer Nature); presented at the conference. <a href="/publication/2025-12-01-heatwave-prediction-xai">Details →</a></p>
<ul>
<li>Built a 10-year (2010–2020) daily climate dataset from eight BMD stations across Bangladesh; used SHAP-based feature selection to identify key predictors of daily maximum temperature</li>
<li>Benchmarked GRU, LSTM, RNN and XGBoost using MSE, MAE and R²</li>
</ul>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #6a1b9a;">
<h2 style="margin-top:0;">Research Experience</h2>
<p><strong>Research Student</strong> — Elite Research Lab (Sep 2026 – Present)</p>
<ul>
<li>Structured mentorship in manuscript writing and framing research contributions under professor and PhD-level mentors</li>
<li>Work in mentor-led research groups on one paper at a time across domains (mostly environmental topics so far); currently co-authoring a team paper targeting <em>IEEE Transactions on Intelligent Transportation Systems</em>, as part of a group paper-writing competition</li>
</ul>
<p><strong>Research Assistant</strong> — AIUB, supervised by Nuzhat Tabassum, Assistant Professor, Dept. of Computer Science (May 2025 – March 2026)</p>
<ul>
<li>Cleaned, preprocessed and engineered features from raw multi-year climate data for heatwave and temperature prediction research</li>
<li>Implemented and evaluated machine learning and time-series models (tree ensembles, GRU, LSTM) with explainability analysis</li>
<li>Prepared technical documents in LaTeX and presentations to communicate research findings</li>
</ul>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #00695c;">
<h2 style="margin-top:0;">Manuscripts in Preparation</h2>
<p><strong>Forecasting Next-Day Maximum Temperature and Hot Days at Bangladeshi Weather Stations: A Leakage-Free Comparison of Machine-Learning, Time-Series and Deep-Learning Models against Persistence.</strong> With N. Tabassum (AIUB).</p>
<ul>
<li>Built and quality-controlled a 44-year (1981–2024) daily BMD dataset (35 stations, plus 8 cities for 2021–2024) with fully logged, code-based checks, including detection of records copied between stations</li>
<li>Designed a strict next-day forecasting setup (inputs up to the issue day only, verified by an automated leakage test) and benchmarked 22 models (tree ensembles, stacking and blending, GA-based feature selection, ARIMA, Prophet, RNN, LSTM, GRU, BiLSTM, CNN-LSTM) against persistence, climatology and ridge regression in 7 cities, with a single test on 2021–2024</li>
<li>Best ensembles reduced the squared error of persistence by 23–24% (ridge regression: 21%); Diebold–Mariano tests showed the champion's gain over ridge to be significant in only 3 of 7 cities; validation-calibrated decision cut-offs raised hot-day F1 by 0.05–0.18</li>
<li>Leave-one-station-out test on 32 stations: pooled XGBoost beat persistence at every station (mean skill 0.25); Morris screening, LIME and permutation importance showed reliance on previous-day maximum temperature, dry-bulb temperature and cloud cover</li>
</ul>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #455a64;">
<h2 style="margin-top:0;">Research Projects</h2>
<p><strong>ML Framework for Next-Day Heat Risk Prediction in Bangladesh</strong> — Independent research project (Jun 2026 – Present)</p>
<ul>
<li>Predict next-day heat risk level (Safe, Caution, Danger, Extreme Danger) for eight Bangladesh cities from previous-day meteorological features (MinTemp, Cloud, Rainfall, DryBulbTemp, Sunshine, WindSpeed), using 11 years of weather data</li>
<li>Risk labels derived from the Heat Index (Rothfusz equation) using MaxTemp and Humidity, both excluded from model inputs to prevent data leakage</li>
<li>Benchmarking XGBoost, Random Forest and LSTM for multi-class prediction; SHAP to identify city-specific risk factors; proposing an early-warning framework</li>
</ul>
<p><strong>Explainable AI in Education for Personalized Learning</strong> (2024 – 2025) — Python, scikit-learn, XGBoost, SHAP</p>
<ul>
<li>XAI framework to predict student GPA and classify stress levels; SHAP identified study hours, sleep and physical activity as key predictors (SVC: 95% accuracy, F1 0.94; Linear Regression R² 0.538)</li>
</ul>
<p><strong>Other Technical Projects</strong></p>
<ul>
<li><strong>Face Recognition System</strong> (Python, TensorFlow): CNN-based recognition with augmentation, evaluated by accuracy, precision, recall and confusion matrix</li>
<li><strong>Data Visualization in Pharmaceutical Evaluation</strong> (R, ggplot2): exploratory analysis and publication-quality visualizations of drug-evaluation data</li>
</ul>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #e65100;">
<h2 style="margin-top:0;">Technical Skills</h2>
<ul>
<li><strong>Programming:</strong> Python, R, SQL</li>
<li><strong>ML &amp; Deep Learning:</strong> scikit-learn, XGBoost, LightGBM, CatBoost, TensorFlow, PyTorch</li>
<li><strong>Time Series:</strong> ARIMA, SARIMA, Prophet, LSTM, GRU, BiLSTM, CNN-LSTM, PyCaret</li>
<li><strong>Forecast Evaluation:</strong> skill scores, Diebold–Mariano test, block bootstrap, leave-one-station-out validation</li>
<li><strong>Explainability:</strong> SHAP, LIME, Morris Sensitivity Analysis, permutation importance</li>
<li><strong>Tools:</strong> Power BI, MySQL, Jupyter, LaTeX, Git / GitHub</li>
</ul>
</div>

<div style="background:rgba(128,128,128,0.12);border-radius:8px;padding:20px 24px;margin:20px 0;border-left:4px solid #2e7d32;">
<h2 style="margin-top:0;">Other Professional Experience</h2>
<p><strong>Content Developer and PPT Presentation Expert, General R&amp;D Department</strong> — Lecture Publications, Dhaka (May 2026 – Present)<br>
Develop academic book content, restructuring complex material into clear explanations aligned with curriculum standards.</p>
<p><strong>Data Analyst</strong> — DC IT Management, Dhaka (Sep 2025 – Feb 2026)<br>
Automated SQL–Python reporting pipelines (monthly reporting time reduced by 30%); built Power BI dashboards used by sales managers.</p>
<p><strong>Junior Data Analyst</strong> — Super Star Group, Dhaka (Dec 2024 – April 2025)<br>
Applied machine learning models to business data to identify trends and support decision-making.</p>
</div>
