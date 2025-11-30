# Ethiopian Banking Apps – Customer Experience Analytics
**10 Academy – Week 2 Challenge**  
**Interim Submission – 30 Nov 2025**

## Task 1 – Data Collection & Preprocessing (Completed – task-1 branch)
- Scraped 1,350+ English reviews using google-play-scraper
- CBE: ~450 | BOA: ~440 | Dashen: ~460 reviews
- Cleaned duplicates, missing data, normalized dates (YYYY-MM-DD)
- Output: `reviews_clean.csv`

## Task 2 – Sentiment & Thematic Analysis (Completed – task-2 branch)
- Used **distilbert-base-uncased-finetuned-sst-2-english** (exact model requested)
- Sentiment scores for 100% of reviews
- 4 custom themes per bank via TF-IDF + rule-based clustering:
  - CBE: Login & OTP, App Crash, Slow Performance, Transfer Failed
  - BOA: Login Problems, Very Slow, Transaction Issues, Poor Support
  - Dashen: PIN/Biometric, Transfer Delay, App Stability, Positive UX
- Output: `reviews_with_sentiment_themes.csv`

## Files in repo
- `reviews_clean.csv` → Task 1
- `reviews_with_sentiment_themes.csv` → Task 2
- `src/` and `notebooks/` folders

All interim KPIs achieved. Ready for Task 3 & final report.
