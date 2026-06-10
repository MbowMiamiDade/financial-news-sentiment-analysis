# financial-news-sentiment-analysis
Exploratory analysis of financial news sentiment and next-day ETF market performance using Python, pandas, and logistic regression.

## Overview
This project explores whether financial news sentiment can help predict next-day market direction and returns for SPY (S&P 500 ETF / large-cap U.S. stocks), DIA (Dow Jones Industrial Average ETF / 30 large blue-chip companies), and IWM (Russell 2000 ETF / small-cap U.S. stocks).

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Excel

## Methodology
- Collected financial news sentiment data
- Created daily net sentiment scores
- Mapped sentiment dates to the next valid trading day
- Adjusted for weekends and market holidays
- Compared sentiment against next-day ETF performance
- Built logistic regression models to test predictive power

## Key Findings
- Negative sentiment did not consistently predict down market days.
- Markets often rose despite negative news sentiment.
- Logistic regression showed weak predictive power, with accuracy around 55%.
- Daily market movements appeared to be influenced by factors beyond headline sentiment alone.

## Files
- `Financial_Sentiment_Project.ipynb` — Python analysis notebook
- `Data together.xlsx` — cleaned dataset
- `.png` files — visualizations from the analysis

## Conclusion
Within this limited sample, financial news sentiment showed only a weak relationship with next-day ETF direction and returns. The project demonstrates data cleaning, trading-day alignment, exploratory analysis, visualization, and basic machine learning.

Initial project upload

## Visualizations

### SPY Up Probability by Sentiment
<img width="504" height="395" alt="image" src="https://github.com/user-attachments/assets/f1f6dedd-03f2-406d-9766-c40f1023b39f" />

### DIA Up Probability by Sentiment
<img width="514" height="395" alt="image" src="https://github.com/user-attachments/assets/6aabc9fc-7aaa-4ae2-b203-c0d939220e06" />

### IWM Up Probability by Sentiment
<img width="519" height="395" alt="image" src="https://github.com/user-attachments/assets/e0da6cff-4bac-4da9-9d75-c380f4091e23" />

### SPY Logistic Regression
<img width="575" height="343" alt="image" src="https://github.com/user-attachments/assets/31b846b4-ca4a-4e17-9ff9-9408257d5c92" />
