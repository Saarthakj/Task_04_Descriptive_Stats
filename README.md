
# Task_04_Descriptive_Stats

This repository contains descriptive statistics analysis for three datasets related to the 2024 US Presidential Election and social media activity.

## 📁 Files
- `2024_fb_ads_president_scored_anon.ipynb`: Analysis of Facebook Ads data
- `2024_fb_posts_president_scored_anon.ipynb`: Analysis of Facebook Posts data
- `2024_tw_posts_president_scored_anon.ipynb`: Analysis of Twitter Posts data

## Features
- Implemented using Pure Python, Pandas, and Polars
- Generates count, mean, min, max, std dev for numeric columns
- Computes unique counts and most frequent values for categorical columns
- Aggregation by relevant columns (`page_id`, `ad_id`, `post_id`, or `tweet_id` depending on dataset)

## How to Run
You can run each notebook in Google Colab or Jupyter Notebook:
1. Open the `.ipynb` file.
2. Run all cells.

## Libraries Used
- Python Standard Library (`csv`, `statistics`, etc.)
- `pandas`
- `polars`

## Datasets (Not included in repo)
Datasets used are not uploaded to GitHub as per instructions. 

## Summary of Insights
- Facebook Ads show strong variance in ad reach and sentiment.
- Facebook Posts and Twitter Posts reflect public engagement patterns around political messaging.
- Using Polars provided faster performance on larger groupings.




