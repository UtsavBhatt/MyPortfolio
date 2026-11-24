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

<div class="project-action-row">
  <a class="work-button work-button-dark" href="https://medium.com/@utsavbhutt2001/do-smart-ml-models-and-algorithms-in-financial-industry-have-to-be-explainable-58f03eb8e50f" target="_blank" rel="noopener">Read the original Medium article ↗</a>
</div>

## The credit-risk example

The article describes a lightweight credit-risk web application that accepts borrower inputs, predicts approve/reject and estimates probability of default. It compares two gradient-boosting models:

- **XGBoost**
- **LightGBM**

The same borrower can receive different probability estimates from the two models because their tree-growth strategies, feature-space partitions, sampling and optimisation choices differ. A model output therefore needs context; a probability should not be mistaken for certainty.

## Making model decisions more interpretable

The example uses two complementary post-hoc explanation techniques:

- **SHAP:** attributes the prediction to input features for an individual case, with explanations that can also be aggregated to understand broader model drivers.
- **LIME:** approximates the model locally around one observation to provide a simpler, human-readable explanation of that prediction.

Together, these techniques help show which factors influenced a model output. They do not, by themselves, prove that a model is fair, correctly calibrated, causally valid or suitable for deployment.

## Why this matters in financial services

Credit decisions affect customers and expose lenders to model, conduct and reputational risk. Explanations can support:

- Review and challenge of individual lending decisions.
- Model validation, documentation and audit trails.
- Communication between data scientists, credit teams, risk committees and customers.
- Ongoing monitoring of model behaviour and limitations.

The practical lesson is that predictive performance is only one dimension of a credit model. Governance, data quality, calibration, fairness and human oversight remain necessary.

## Scope and limitations

The article's application is a demonstration built using a publicly available dataset. As noted in the original article, its model performance and probability estimates may be inaccurate. It should be treated as an educational prototype, not a production credit-underwriting system or evidence of regulatory compliance.

[Return to Concepts & Theory Knowledge]({{ '/projects/' | relative_url }}#concepts-theory)
