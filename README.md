# financial-news-sentiment-analysis
Exploratory analysis of financial news sentiment and next-day ETF market performance using Python, pandas, and logistic regression.

## Overview
This project explores whether financial news sentiment can help predict next-day market direction and returns for SPY, DIA, and IWM.

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
