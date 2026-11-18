---
title: "USD/INR Currency Derivatives"
permalink: /projects/usd-inr-currency-derivatives/
layout: single
author_profile: false
classes: wide portfolio-page
---

<p class="eyebrow">CURRENCY MARKETS · DATA ANALYSIS</p>

# USD/INR Currency Derivatives Dataset

A historical dataset and analytical workflow covering the USD/INR spot market, exchange-traded futures and options.

## Scope

The dataset covers **1 January 2018 to 31 December 2025** and contains approximately **1.7 million options records**, alongside supporting spot and futures data.

## Data and processing

- **Options:** trade date, expiry, settlement price, option type and strike; derived time to expiry and tenor buckets.
- **Implied volatility and sensitivity:** calculated implied volatility and delta, with 25-delta call and put volatility and strike measures.
- **Spot:** RBI reference spot rates, daily log returns and 30-day annualised volatility.
- **Futures:** settlement prices, spot mapping, forward points and tenor classification.

## What this dataset supports

The structure can be used to study the evolution of the USD/INR volatility surface, tenor-specific pricing, forward premia and the relationship between option-implied risk and realised market conditions.

It also provides a foundation for further work on risk reversals as macro indicators, volatility regime analysis and FX stress testing. Those extensions should be treated as separate research questions rather than results established by the dataset itself.

## Reproducibility and scope

The dataset is historical and analytical. Derived fields depend on the calculation conventions and data quality of the underlying source files. Any use for trading, valuation or risk decisions requires independent validation of inputs, conventions and calculations.

**Published dataset:** the Kaggle dataset link and notebook links will be added to this page once the canonical public URLs are attached.
