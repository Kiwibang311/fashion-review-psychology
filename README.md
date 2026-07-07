# Beyond the Surface: Decoding Psychological Biases in Fashion E-Commerce Reviews

## Overview
This repository contains the data processing scripts and analytical notebooks for the MSc dissertation:

**"Beyond the Surface: Decoding Psychological Biases in Fashion E-Commerce Reviews"**
Diyun Chen | MSc Business Analytics | Trinity College Dublin | 2025

## Research Summary
This study examines the psychological mechanisms underlying rating–recommendation inconsistency in fashion e-commerce reviews, drawing on cognitive dissonance theory, impression management theory and Newcomb's Paradox.

## Repository Structure
├── data_processing.ipynb    # Main analytical notebook
├── data/
│   ├── womens_clothing_reviews.csv    # Primary dataset (Kaggle)
│   └── reddit_comments.csv            # Supplementary dataset
└── figures/
├── rating_distribution_bw.png
├── h2_total_bw.png
├── vader_compound_stacked_bw.png
└── dissonance_by_department_bw.png

## Data Sources
- **Primary dataset**: Women's Clothing E-Commerce Reviews — [Kaggle](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
- **Supplementary dataset**: Reddit comments scraped from r/femalefashionadvice and r/frugalfemalefashion

## Dependencies
python >= 3.8
pandas
numpy
matplotlib
seaborn
scipy
vaderSentiment
sentence-transformers
bertopic
transformers

## Note on Visualisations
Figures with `_bw` suffix are greyscale versions produced for the dissertation submission. Other plots retain their original colour formatting for readability.

## Citation
If you use this code or data in your research, please cite:
Chen, D. (2026). Beyond the Surface: Decoding Psychological Biases in Fashion E-Commerce Reviews. MSc Dissertation, Trinity College Dublin.
