---
layout: default
title: Unit 6
nav_order: 6
---

# Unit 6

## Reflection
### What?
Unit 6 focused on implementing K means clustering in Python with scikit learn. The unit moved from theory into practice by covering preprocessing, feature selection, scaling, K selection, and evaluation, and I applied this workflow across the Iris, Wine, and WeatherAUS datasets.
### So what?
This unit showed me that clustering quality depends heavily on the decisions made before fitting the model. In the seminar tasks, K means aligned only partly with the Iris classes, performed very strongly on the Wine data, and produced much weaker separation on WeatherAUS, where silhouette values were low. That contrast made it clear that the same algorithm can perform very differently depending on feature space, overlap between groups, and preprocessing quality.
### Now what?
Going forward, I want to justify preprocessing, feature choice, and K selection more explicitly whenever I use clustering. Unit 6 reinforced that cluster labels are exploratory outputs rather than ground truth, so I need to evaluate them carefully and explain their limitations instead of treating them as definitive categories.

## Artefacts
### Summary
<iframe src="{{ site.baseurl }}/files/unit-06/Unit_6_Summary.pdf"
        width="100%" height="800"
        style="border:1px solid #ddd;"></iframe>

### Seminar Notes
<iframe src="{{ site.baseurl }}/files/unit-06/Unit_6_Seminar_Notes.pdf"
        width="100%" height="800"
        style="border:1px solid #ddd;"></iframe>

### K-mean Clustering Exercise
<iframe src="{{ site.baseurl }}/files/unit-06/K-means_clustering.html"
        width="100%" height="900" style="border:1px solid #ddd;"></iframe>



