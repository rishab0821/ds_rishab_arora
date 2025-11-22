# ds_rishab_arora
Data Science assignment exploring the relationship between trader performance and market sentiment using trading logs and the Fear–Greed Index. Includes full Colab notebook, daily aggregation, sentiment analysis, EDA, statistical testing, regression modeling, insights, and final report.

Trader Performance vs Market Sentiment

Author: Rishab Arora
Email: rishab2104@gmail.com

Google Colab Notebook:
🔗 https://colab.research.google.com/drive/1dpvetDvBleROQIghGO_vD45VIsMLGxAm?usp=sharing

Repository Structure
ds_rishab_arora/
├── notebook_1.ipynb               # Main Colab notebook
├── csv_files/                     # Processed datasets
│   ├── daily.csv
│   ├── daily_no_outliers.csv
│   ├── model_input.csv
│   ├── raw_sentiment_clean.csv
├── outputs/                       # Visual charts, plots
│   ├── *.png / *.jpg
├── ds_report.pdf                  # Final analysis report
└── README.md                      # Documentation

Project Overview:

This project analyzes how market sentiment (Fear–Greed Index) influences trader performance.
The analysis explores:

>Daily PnL patterns

>Volume activity

>Trade count patterns

>Sentiment-based performance differences

>Regression modeling to identify drivers of trader performance

The objective is to uncover hidden relationships between sentiment phases and trading outcomes, enabling smarter, data-driven strategies.

Key Steps in the Analysis
1. Data Cleaning

  Standardized timestamps

  Filtered valid trading actions

  Computed realized PnL correctly

  Cleaned sentiment dataset

2. Feature Engineering

  Daily-level aggregation

  Merged sentiment

  Computed lag features

  Built model_input dataset

3. Exploratory Data Analysis

  PnL over time

  Cumulative returns

  Trade activity

  Volume (log-scale)

  Sentiment-wise performance

4. Modeling

  Regression-style analysis

  Sentiment impact estimation

  Volume & lag effects

Visual Outputs
All visualizations (PNL trends, sentiment PNL distributions, volume charts, etc.) are stored in: /outputs/

Report
The full professional report summing up methodology, insights, and recommendations is available at: ds_report.pdf

Reproducibility - To reproduce results:

Open notebook_1.ipynb

Run all cells in order on Google Colab

Outputs will be generated automatically

Contact

If you have any questions or would like to discuss this project further:
📧 rishab2104@gmail.com
