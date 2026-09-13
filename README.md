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
- `Untitled-1.ipynb` — [brief description of what this notebook covers]
- `Untitled-2.ipynb` — [brief description of what this notebook covers]

## Tech stack
Python, scikit-learn, pandas

## Author
Patrick Koomson — PhD Researcher, Management Science, Beijing University of
Posts and Telecommunications
[LinkedIn](https://www.linkedin.com/in/koomson-patrick-a2ab86402)

## License
CC0-1.0
