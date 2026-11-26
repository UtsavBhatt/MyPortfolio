---
title: "Explainable AI in Financial Services"
permalink: /projects/explainable-ai-credit-risk/
layout: single
author_profile: false
classes: wide portfolio-page project-detail
---

<p class="eyebrow">AI / ML · CREDIT RISK · MODEL GOVERNANCE</p>

# Do Smart ML Models in Finance Have to Be Explainable?

This article examines a practical question in financial machine learning: when a model informs a credit decision, should the people using that decision be able to understand why it was produced?

## The credit-risk example

The original article describes a demonstration application that accepts borrower inputs, predicts approve/reject and estimates probability of default. It compares two gradient-boosting models:

- **XGBoost**
- **LightGBM**

The models can produce different probability estimates for the same borrower. Model choice and implementation therefore matter; a probability should not be treated as certainty.

## Explaining individual predictions

The example considers two post-hoc explanation methods:

- **SHAP** attributes a prediction to input features and can also be used to examine broader patterns across observations.
- **LIME** approximates model behaviour locally around an individual observation to provide a simpler explanation of that prediction.

These methods can help a reviewer understand what influenced an output. They do not, by themselves, establish that a model is fair, well calibrated, causally valid or suitable for production use.

## Why it matters

Credit decisions affect customers and expose lenders to model, conduct and reputational risk. Explanations can support review of individual decisions, model validation, audit trails and communication between data science, credit and risk teams.

## Scope and limitations

The application is an educational demonstration using a publicly available dataset. Its model performance and probability estimates may be inaccurate. It is not a production underwriting system and does not establish regulatory compliance.

<div class="project-action-row">
  <a class="work-button work-button-dark" href="https://medium.com/@utsavbhutt2001/do-smart-ml-models-and-algorithms-in-financial-industry-have-to-be-explainable-58f03eb8e50f" target="_blank" rel="noopener">Read the original Medium article ↗</a>
</div>

[Back to Concepts & Theory Knowledge]({{ '/projects/' | relative_url }}#concepts-theory)
