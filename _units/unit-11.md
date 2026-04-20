---
layout: default
title: Unit 11
nav_order: 11
---

# Unit 11

## Reflection
### What?
Unit 11 focused on model selection and evaluation, with emphasis on bias and variance, resampling, cross validation, ROC and AUC, and the idea that the best model depends on context rather than one metric alone. In the activity, I tested how changing LogisticRegression regularization strength affected AUC on the Iris and breast cancer datasets.
### So what?
This unit showed me that strong model performance cannot be judged from a single run or a single score. In the activity, reducing C to 0.01 lowered AUC on both datasets, while weaker regularization kept performance high. That made the effect of hyperparameter choice much more concrete and reinforced that evaluation must be controlled and comparative. It also helped me see that model quality involves trade offs between fit, generalization, and the cost of different types of error.
### Now what?
Going forward, I want to be more systematic in how I compare models, choose metrics, and justify threshold or parameter decisions. Unit 11 reinforced that reliable machine learning depends as much on evaluation design as on the algorithm itself.

## Artefacts

### Summary
<iframe src="{{ site.baseurl }}/files/unit-11/Unit_11_Summary.pdf"
        width="100%" height="800"
        style="border:1px solid #ddd;"></iframe>

### Activity - Model Performance Measurement
<iframe src="{{ site.baseurl }}/files/unit-11/Unit11_model_Performance_Measurement.html"
        width="100%" height="800"
        style="border:1px solid #ddd;"></iframe>

### Activity Notes
<iframe src="{{ site.baseurl }}/files/unit-11/Unit_11_Activity_Notes.pdf"
        width="100%" height="800"
        style="border:1px solid #ddd;"></iframe>




