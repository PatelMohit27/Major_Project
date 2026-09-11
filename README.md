# Major_Project
# The Data-Driven Social Engagement Initiative

A Data Science project that decodes the "science of relatability" in digital content — using statistical modeling, NLP, and A/B testing to identify, measure, and optimize content that fosters deep human connection, replacing creative guesswork with evidence-based analytics.

## 📌 Project Overview

This project builds a unified analytics ecosystem that integrates content performance tracking, virality prediction, sentiment analysis, A/B testing, and an interactive dashboard — all aimed at understanding which topics, formats, and posting strategies drive the strongest audience engagement.

## 🧩 Core Modules

1. **Content Performance Tracker** — Structures raw engagement metrics (shares, saves, retention rate) into a clean dataset.
2. **Virality Prediction Engine** — Calculates a custom "Viral Coefficient" per post, weighing high-value actions (shares & saves) over passive actions (likes).
3. **Audience Sentiment Analyzer (NLP)** — Analyzes comments using TextBlob and linguistic trigger detection to classify them as "Relatable" or "Neutral," validating problem awareness.
4. **A/B Testing Framework** — Runs statistical significance tests (independent t-tests) comparing content formats (Short vs. Long) and hooks (Visual vs. Text).
5. **Engagement Optimization Recommender** — Suggests the optimal topic, format, hook, and posting time based on historical data.
6. **Growth Visualization Dashboard** — An interactive Streamlit dashboard visualizing viral coefficients, sentiment distribution, and save-to-share ratios.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Data Processing | Python (Pandas, NumPy) |
| NLP & Text Analysis | NLTK, TextBlob |
| Statistical Testing | SciPy, Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Dashboard Frontend | Streamlit |

## 📂 Project Structure

```
├── content_performance_data.csv    # Structured content performance dataset
├── comments_sentiment_data.csv     # Comments tagged with sentiment analysis
├── ab_test_results.csv             # A/B testing statistical results
├── strategy_recommendation.txt     # Auto-generated content strategy
├── viral_coefficient_by_topic.png  # Viral coefficient visualization
├── posting_hour_analysis.png       # Best posting hour visualization
├── dashboard.py                    # Streamlit dashboard application
├── Strategy_Report.docx            # Full strategy report
└── README.md                       # Project documentation
```

## insights 
<img width="1871" height="867" alt="Screenshot 2026-09-11 101723" src="https://github.com/user-attachments/assets/66e459c4-1cde-469f-96b7-be044732f8d9" />
<img width="1591" height="858" alt="Screenshot 2026-09-11 101759" src="https://github.com/user-attachments/assets/ee30673a-792b-4c75-a960-e4c9ecb1e4a4" />
<img width="1785" height="942" alt="Screenshot 2026-09-11 101838" src="https://github.com/user-attachments/assets/c80b8415-4ddf-4204-a53e-5c74d61fcfae" />


## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install pandas numpy nltk textblob matplotlib seaborn scikit-learn streamlit scipy
   ```
2. Run the analysis notebook to generate the datasets and metrics.
3. Launch the dashboard:
   ```bash
   streamlit run dashboard.py
   ```

## 🔑 Key Findings

- **Loneliness**, **Social Anxiety**, and **Overthinking** emerged as the topics with the highest average Viral Coefficient, confirming that emotionally vulnerable, relatable content drives significantly more shares and saves than lighter topics.
- **8 PM (20:00)** was identified as the strongest posting hour based on average viral coefficient.
- A/B testing statistically validated which content format and hook type drive higher engagement (see `ab_test_results.csv` for exact figures).

## 📦 Deliverables

- ✅ Fully functional Analytics Dashboard
- ✅ Structured Dataset (content performance + comments)
- ✅ NLP Sentiment Model
- ✅ Strategy Report
- ✅ Content Series (sample topic-based scripts used as test subjects)

## 👤 Author 

*Mohit Patel*
