---
layout: page
title: Chokepoint detection using high resolution imagery
description: This project was class project done by me on my machine learning class in Brown University.
img: assets/img/choke_pt1.png
importance: 7
category: Professional
---

The major critical control of the flow of water is the chokepoints which are the bedrocks in the river. These
bedrocks play a great role in hydrological connectivity. When there is low flow the bedrocks in the river
obstruct the flow of the river and during the high flow the rivers overtop them forming white water riffle.
Identifying them manually is a very tedious process. So, in this project, I have various object detection
models for detecting bedrocks in the rivers. I used Single Shot Detector (SSD), Faster Region-based
Convolutional Neural Network (Faster RCNN) and You look only once (Yolo)s object detection algorithms
to detect bedrocks in the rivers. I used panchromatic Worldview imagery of 0.5 m resolution for this
purpose. None of the models produce high accuracy. However faster RCNN model was better than other
models in terms of precision and recall. The reason for bad results may be the use of panchromatic images
because the model got confused with objects and background. More training data, pansharpened images,
and the use of precise parameter tuning might increase the result

<a href="https://github.com/wagle1996/Bedrock_detection">Go to this github link to see source code</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/choke_pt1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/choke_pt2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/choke_pt3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Detection of choke points and image labelling
</div>




