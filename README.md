#Web3 Trader Sentiment Analysis — Fear vs Greed Prediction

<p>This project explores the relationship between trader behavior and market </P><p>sentiment using the Bitcoin Fear & Greed Index and real trading data. </P>
<p>The goal was to analyze how profit, trade volume, and activity differ during Fear and Greed periods,</P>
<p>and to build a simple machine learning model capable of predicting the </P><p>sentiment of a given trading day.</P>

<p>Using Python (Pandas, Seaborn, Scikit-learn) in Google Colab, I performed data</P> <p>cleaning, feature aggregation, exploratory analysis, </P>
<p>and visualization to uncover behavioral patterns.</P>
<p>I then developed baseline models — Logistic Regression, Decision Tree, and </P><p>Random Forest — achieving up to ~74% accuracy (Decision Tree). </P>
<p>The study revealed that average daily profit (closed_pnl) is the most </P><p>influential factor distinguishing Greed days from Fear days.</P>

<p>This project demonstrates a complete data science workflow — from dataset </P><p>preparation to model evaluation and report generation. </P>
<p>The final analysis provides clear insights into trader psychology, showing that </P><p>market optimism correlates with profitability and trade confidence,</P>
<p>while fear is marked by cautious, low-return behavior.</P>

```
ds_sameerchauhan/
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   ├── merged_trader_sentiment.csv
│   ├── sample_merged.csv
│   └── sentiment_summary.csv
├── outputs/
│   ├── avg_profit_by_sentiment.png
│   ├── daily_avg_profit_trend.png
│   ├── fear_greed_decision_boundaries.png
│   ├── total_volume_by_sentiment.png
│   ├── trade_side_by_sentiment.png
│   └── trade_size_by_sentiment.png
├── Notebook1.ipynb
├── ds_report.pdf
└── README.md
```

