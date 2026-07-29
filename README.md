# Spotify Artist Career Ranking Framework

A data-driven framework for evaluating artist career performance using Spotify daily chart data and statistical ranking methods.

## Overview

This project analyzes Spotify daily chart activity spanning **2017–2026** to evaluate artist performance across multiple dimensions of streaming success. Rather than relying on a single metric, the framework combines engineered features that capture different aspects of artist performance, including:

- Stream statistics
- Peak performance
- Longevity
- Chart dominance
- Stability
- Career trajectory

The engineered features are integrated into a unified **Career Score** using statistical feature weighting through **Principal Component Analysis (PCA)** and final ranking using **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)**.

## Dataset

- Spotify daily chart data
- Period: **2017–2026**
- Coverage: **73 countries**
- Target artist dataset extracted from the full Spotify chart archive

## Methodology

The analysis follows the workflow below:

1. Data extraction and preprocessing
2. Artist identification using standardized artist mappings
3. Feature engineering across multiple performance dimensions
4. Feature standardization
5. PCA-based feature weighting
6. Career Score calculation using TOPSIS
7. Exploratory visual analysis

## Project Structure

```
├── Spotify streaming Era Analysis.ipynb
├── stability_metric.csv
├── artist_career_metric_score.csv
├── trajectory_metric.csv
├── charts_songs_daily_targets.csv
├── career_metric_feature_weights.csv
├── dominance_metric.csv
├── longevity.csv
├── peak_stats.csv
├── weekly_trajectory.csv
├── stream_stats.csv
├── weekly_dominance_metrics.csv
└── README.md
```

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly

## Notes

This framework evaluates artist performance **within the Spotify streaming era** using measured Spotify chart metrics. Differences in streaming availability, platform adoption, and audience behavior across eras should be considered when interpreting the results.

## AUTHOR

**Abiodun Adeteye**
