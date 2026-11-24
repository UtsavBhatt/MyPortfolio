---
title: "Explainable AI in Financial Services"
permalink: /projects/explainable-ai-credit-risk/
layout: single
author_profile: false
classes: wide portfolio-page project-detail
---

<p class="eyebrow">AI / ML · CREDIT RISK · MODEL GOVERNANCE</p>

# Do Smart ML Models in Finance Have to Be Explainable?

A practical exploration of explainable machine learning in financial services, using a credit-risk decision example. The central question is not only whether a model predicts accurately, but whether a lender can understand, review and challenge the reasons behind an individual decision.


## The credit-risk example

The article describes a lightweight credit-risk web application that accepts borrower inputs, predicts approve/reject and estimates probability of default. It compares two gradient-boosting models:

- **XGBoost**
- **LightGBM**

The same borrower can receive different probability estimates from the two models because their tree-growth strategies, feature-space partitions, sampling and optimisation choices differ. A model output therefore needs context; a probability should not be mistaken for certainty.

<div class="project-action-row">
  <a class="work-button work-button-dark" href="https://medium.com/@utsavbhutt2001/do-smart-ml-models-and-algorithms-in-financial-industry-have-to-be-explainable-58f03eb8e50f" target="_blank" rel="noopener">Read the original Medium article ↗</a>
</div>

## Scope and limitations

The article's application is a demonstration built using a publicly available dataset. As noted in the original article, its model performance and probability estimates may be inaccurate. It should be treated as an educational prototype, not a production credit-underwriting system or evidence of regulatory compliance.

[Return to Concepts & Theory Knowledge]({{ '/projects/' | relative_url }}#concepts-theory)
