# Customer-Complaints-Analytics
Power BI dashboard for analyzing real-world financial complaints with sentiment insights
This project analyzes over 380,000 real-world financial complaints from the U.S. Consumer Financial Protection Bureau (CFPB) dataset. It uses sentiment analysis, reporting automation, and interactive Power BI visuals to uncover key patterns in consumer dissatisfaction.

---

## Dashboard Features

- Total Complaints KPI Card
- Monthly trend of complaint volumes
- Top Products and Top Companies by complaint volume
- Sentiment Analysis (Positive / Neutral / Negative) using TextBlob
- Resolution vs Disputed breakdown
- Escalation Funnel to highlight complaint journey
- Slicers to filter by sentiment, product, state, and company

---

## Dataset

- Source: [Kaggle – Consumer Finance Complaints](https://www.kaggle.com/datasets/cfpb/us-consumer-finance-complaints)
- Rows: 1.2M+ complaints (filtered to ~383K with narratives)
- Preprocessing:
  - Dropped missing narratives
  - Performed sentiment analysis using TextBlob
  - Cleaned categories and null values
  - Exported cleaned data for visualization in Power BI

---

## Tools Used

- Python (Pandas, TextBlob, NLTK)
- Power BI Desktop
- Git, GitHub
- NLP for sentiment classification

---

## Files in This Repo

| File                          | Description                                |
|-------------------------------|--------------------------------------------|
| `processed_complaints.csv`   | Cleaned dataset with sentiment labels       |
| `Customer_Complaints_Analytics.pbix` | Power BI dashboard file (LFS-tracked)     |
| `screenshots/`               | Preview images of the dashboard            |

Note: `.pbix` file is stored using Git LFS due to size >25MB.

---

