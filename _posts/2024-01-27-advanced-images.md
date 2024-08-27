---
layout: post
title: a post with advanced image components
date: 2024-01-27 11:46:00
description: this is what advanced image components could look like
tags: formatting images
categories: sample-posts
thumbnail: assets/img/happy.jpg
---

I enjoy knitting, especially sewing clothes for dolls, which somewhat fulfills my dream of becoming a fashion designer. Painting and exercising also provide relaxation in my busy life. Additionally, visiting art galleries is one of my favorite activities.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bear.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/rabbit.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad2.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

