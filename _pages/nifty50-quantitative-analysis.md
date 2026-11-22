---
title: "Nifty 50 Quantitative Analysis"
permalink: /projects/nifty50-quantitative-analysis/
layout: single
author_profile: false
classes: wide portfolio-page project-detail
---

<p class="eyebrow">EQUITY MARKETS · PYTHON · PORTFOLIO ANALYTICS</p>

# Nifty 50 Quantitative Analysis & Portfolio Theory

A Python-based workflow that moves from historical stock-price data to portfolio risk analysis, interactive comparisons and forward-looking simulations.

<div class="project-action-row">
  <a class="work-button work-button-dark" href="https://colab.research.google.com/drive/1jatenuG5Xxj3eGq1PZwABdECtm60Q63C?usp=sharing" target="_blank" rel="noopener">Open Google Colab notebook ↗</a>
  <span class="project-status-note">Notebook requires the companion Data.xlsx workbook.</span>
</div>

## What the notebook covers

<div class="project-stat-grid">
  <div><strong>6</strong><span>analysis stages</span></div>
  <div><strong>252</strong><span>trading-day simulation horizon</span></div>
  <div><strong>1,000</strong><span>Monte Carlo paths in the illustrated run</span></div>
</div>

### 1. Data preparation and exploratory analysis
The notebook cleans the source workbook, prepares daily returns and explores cumulative performance and return distributions for the selected equities and Nifty 50 benchmark.

### 2. Statistical and portfolio metrics
The workflow includes annualised return and volatility, correlation analysis, beta estimation, Sharpe and Sortino ratios, historical Value at Risk and rolling volatility.

### 3. Interactive market dashboard
A Plotly dashboard allows a selected stock to be compared with the Nifty 50 index over the available sample.

### 4. Monte Carlo simulation
The notebook uses Geometric Brownian Motion to simulate potential price paths over a one-year horizon. The displayed example uses 1,000 paths and reports percentile paths alongside a median path.

### 5. Portfolio construction and risk stress-testing
A custom portfolio function accepts stock quantities, a 252-day horizon and a maximum-loss tolerance. It estimates a distribution of future portfolio values and compares the modelled loss with the chosen risk limit.

## Selected output

The notebook includes an interactive cumulative-performance comparison and simulated portfolio distributions. These are analytical outputs generated from historical inputs and model assumptions; they are not price targets or investment recommendations.

## Tools and methods

- Python: pandas, NumPy and Matplotlib
- Plotly for interactive visualisation
- Historical return and risk statistics
- Beta, Sharpe ratio, Sortino ratio and Value at Risk
- Geometric Brownian Motion and Monte Carlo simulation

## Reproducing the analysis

1. Open the Colab notebook using the link above.
2. Upload the companion workbook named `Data.xlsx` to the Colab session when prompted by the notebook.
3. Run the notebook cells in order, starting with data preparation.
4. The notebook uses the workbook's master data and daily returns sheets.

The workbook is not hosted on this page yet. A public download link will be added when the source file is published separately.

## Scope and limitations

Results depend on the historical sample, data cleaning, selected stocks and modelling assumptions. Geometric Brownian Motion is a simplifying model and does not capture every market regime, jump or liquidity constraint. Portfolio simulations should be interpreted as scenario analysis rather than forecasts.

[Back to all work]({{ '/projects/' | relative_url }})
