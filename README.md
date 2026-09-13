A Two-Stage Clustering Architecture for Cross-Cultural Telecom Customer Segmentation
## Overview
This project builds a two-stage clustering pipeline for segmenting telecom
customers across multiple countries and cultures, paired with a recommendation
layer that matches each segment to relevant offers. Rather than assuming a
single segmentation model transfers cleanly from one market to another, the
architecture is designed to hold up across cultural and behavioral
differences in customer data.

## What it does
- **Stage 1 — Behavioral clustering:** groups customers by usage patterns and
  behavioral signals within each market
- **Stage 2 — Cross-cultural refinement:** adjusts and validates segments so
  they generalize meaningfully across different countries/regions, rather than
  overfitting to one market's customer profile
- **Recommendation layer:** maps each resulting segment to relevant offers or
  actions

## Use case
Built for telecom and subscription businesses operating in multiple markets
that need a segmentation approach robust enough to inform targeting and
offer design across regions — not just within a single home market.

## Contents
- `Untitled-1.ipynb` — Generate synthetic datasets (Ghana & India), run preprocessing, clustering (GMM, Spectral, DBSCAN/HDBSCAN fallback),
UMAP/TSNE for visualization, construct similarity graph and spectral embeddings as proxy for GraphSAGE, and produce Figures 1-5 and Tables 1-4.
- `Untitled-2.ipynb` — PPP-Normalization, Culture-Aware Feature Engineering, Two-Stage Clustering Architecture, LightGBM Model for Churn Prediction, Generate Tables and Figures, and Results.

## Tech stack
Python, scikit-learn, pandas

## Author
Patrick Koomson — PhD Researcher, Management Science, Beijing University of
Posts and Telecommunications
[LinkedIn](https://www.linkedin.com/in/koomson-patrick-a2ab86402)

## License
CC0-1.0
