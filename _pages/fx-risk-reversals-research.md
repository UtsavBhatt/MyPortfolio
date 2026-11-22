---
title: "FX Options as Early Indicators of Macroeconomic Risk"
permalink: /projects/fx-risk-reversals-research/
layout: single
author_profile: false
classes: wide portfolio-page project-detail
---

<p class="eyebrow">ACADEMIC RESEARCH · FX OPTIONS · MACROECONOMICS</p>

# FX Options as Early Indicators of Macroeconomic Risk

### Evidence from USD/INR risk reversals, 2018–2025

This research paper examines whether changes in USD/INR option risk reversals can provide an early signal of shifts in market expectations and periods of macroeconomic stress.

<div class="project-action-row">
  <a class="work-button work-button-dark" href="https://www.kaggle.com/datasets/utsavbhattt/fx-currency-derivatives-data-2018-2025-usd-inr" target="_blank" rel="noopener">Access the underlying dataset ↗</a>
  <a class="work-button work-button-light" href="{{ '/projects/usd-inr-currency-derivatives/' | relative_url }}">Dataset project details ↗</a>
</div>

## Research question

Do changes in USD/INR risk reversals reflect demand for protection against rupee depreciation before that stress becomes visible in the spot exchange rate?

Risk reversals compare the implied volatility of out-of-the-money USD calls and puts. In the paper, they are treated as a market-based measure of asymmetric demand for currency protection and sentiment.

## Data and approach

The study uses the author's USD/INR derivatives dataset covering 2018–2025, including spot rates, option implied volatility, delta, tenor, expiry and settlement information.

The analysis combines:
- Descriptive analysis of spot rates and option skew.
- Short- and medium-tenor risk-reversal trends.
- Event-based comparisons around the March 2020 COVID-19 shock and 2022 geopolitical and monetary-policy developments.
- Granger-causality testing to examine lead–lag relationships between changes in risk reversals and spot returns.

## Findings reported in the paper

**March 2020 event window:** The paper reports that one-month 25-delta risk reversals rose from a baseline near 0.40% to above 3.00% ahead of the sharpest spot-market move in the event window.

**2022 risk-off period:** The paper describes persistently elevated three-month risk reversals during a period of global monetary tightening and geopolitical uncertainty.

**Lead–lag test:** The paper reports its strongest result at a three-day lag, with a p-value of 0.009. This is presented as evidence of a possible short-horizon information relationship, not proof that risk reversals cause subsequent spot movements.

## Why this question matters

Spot rates show the traded exchange rate. Option prices also contain information about the price investors are willing to pay for asymmetric protection. Comparing the two may help analysts understand how market concern evolves when spot volatility is subdued.

Potential applications include currency-risk monitoring, corporate treasury hedging and macro-financial surveillance. These are possible uses of the signal, not tested operational outcomes of this study.

## Limitations

This is an academic, observational study focused on a single currency pair. Event comparisons and Granger-causality tests do not establish structural causation or guarantee out-of-sample predictive performance. The paper's dataset-count descriptions also require reconciliation before a final academic submission or external publication.

## Related work

[USD/INR Currency Derivatives Dataset]({{ '/projects/usd-inr-currency-derivatives/' | relative_url }}) · [Kaggle dataset](https://www.kaggle.com/datasets/utsavbhattt/fx-currency-derivatives-data-2018-2025-usd-inr)

[Back to all work]({{ '/projects/' | relative_url }})
