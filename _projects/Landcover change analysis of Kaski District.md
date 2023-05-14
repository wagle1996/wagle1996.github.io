---
layout: page
title: 
description: This project was done in collaboration with Dr. Tri Dev Acharya.
img: assets/img/multi1.png
importance: 2
category: work
---

The study deals with the application of Google Earth Engine (GEE), Landsat data and ensemble-learning methods (ELMs) to map land cover (LC) change over a decade in the Kaski district of Nepal. As Nepal has experienced extensive changes due to natural and anthropogenic activities, monitoring such changes are crucial for understanding relationships and interactions between social and natural phenomena and to promote better decision-making. The main novelty lies in applying the XGBoost classifier for LC mapping over Nepal and monitoring the decadal changes of LC using ELMs. To map the LC change, a yearly cloud-free composite Landsat image was selected for the year 2010 and 2020. Combining the annual normalized difference vegetation index, normalized difference built-up index and modified normalized difference water index, with elevation and slope data from shuttle radar topography mission, supervised classification was performed using a random forest and extreme gradient boosting ELMs. Post classification change detection, validation and accuracy assessment were executed after the preparation of the LC maps. Three evaluation indices, namely overall accuracy (OA), Kappa coefficient, and F1 score from confusion matrix reports, were calculated for all the points used for validation purposes. We have obtained an OA of 0.8792 and 0.875 for RF and 0.8926 and 0.8603 for XGBoost at the 95% confidence level for 2010 and 2020 LC maps, which are better for mountainous terrain. The applied methodology could be significant in utilizing the big earth observation data and overcoming the traditional computational challenges using GEE. In addition, the quantification of changes over time would be helpful for decision-makers to understand current environmental dynamics in the study area.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Landcover change maps and change analysis in Kaski District
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Representation of models used in landcover mapping: (a) Single tree out of all samples; (b) bagging grows tree parallel with subsamples; (c) boosting grows tree sequentially with weighted samples.
</div>

In Nepal, huge snow and cloud covers make it impossible to map a large extent with the single-day image or even with the monthly composite image. Hence, the annual median composite adopted in this study can be adopted to make the LC map of entire Nepal which is openly available in the GEE platform. Such availability of data without extensive preprocessing and allocating substantial storage makes the process very fast and efficient. Future work can focus on implementing data fusion techniques for integrating Landsat and Sentinel imagery that may furnish greater accuracies with finer resolutions. Various other machine learning models with multitemporal resolutions (summer and winter composites) can be used for better understanding the models’ performance in LC mapping.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/multi7.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    location of traning data in the Kaski District.
</div>




