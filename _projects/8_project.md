---
layout: page
title: Waterbody mapping using image segmentation
description: This project was class project done by me on my computer vision class in Brown University.
img: assets/img/deeplearning.png
importance: 8
category: Professional
---

Water is an essential part of a living ecosystem, as it is
necessary for the survival of all living beings. As a result,
many scientific tasks require up-to-date information on spa-
tial distribution of water; to be able to track trends in water
resources over time. To do this, it is common to look at wa-
ter maps, which are masks of satellite images where each
pixel is either water or non-water: In this project, we wanted
to automatically generate water maps using deep learning
techniques. We collected Landsat 8 imagery with existing
water maps to train a U-Net model, which has previously
been shown to achieve high accuracy in image segmentation
tasks. After training for 100 epochs, our model obtained
accuracy of over 99% on the test set. While it was able to
identify large regions of water; some of the small water bod-
ies and finer details were often misclassified by our model.
Counterintuitively, data augmentation did not produce better
results and instead reduced the accuracy. However, these
results are still very promising and open the door to quick
and easy water mapping in the future.
<a href="https://github.com/wagle1996/Mapping_waterbody">Go to this github link to see source code</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/deeplearning.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dl3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dl4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Deploy of model in training and test data, accuracy and epoch loss of model and model architecture
</div>




