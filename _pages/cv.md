---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
=========

<div style="display: flex; justify-content: space-between;">
    <div>MSc in Communications Engineering	</div>
    <div>08/2022 - present</div>
</div>

- Nanyang Technological University

<div style="display: flex; justify-content: space-between;">
    <div>Beng in Communication Engineering (Yingcai Honors Program of UESTC)</div>
    <div>09/2018 - 07/2022</div>
</div>

* University of Electronic Science and Technology of China
  * Grade Points: 3.65/4
  * TOEFL(iBT): 103

Research experience
===================

* Summer 2022: Senior Student Researcher
* [Supervisor：Dakun Lai(Professor), UESTC-BMI-EP](https://faculty.uestc.edu.cn/dklai/zh_CN/index.htm)
  * Established a comprehensive database by integrating data from three public databases and conducted meticulous preprocessing. The database comprised a total of 855,882 heartbeat activities, including 30 segments of Paroxysmal Atrial Fibrillation (PAF) and 30 segments of normal heart rate.
  * Designed a robust semi-supervised learning model utilizing a convolutional auto-encoder (CAE) architecture. Implemented on TensorFlow, the model achieved an impressive accuracy of 90.16% using only 10% of the available training data for binary classification of ECG signals.
  * Successfully published the research outcomes in the prestigious conference EMBC'23, and I am going to give an oral presentation to highlight the significance of the findings.

Skills
======

* Python
  * PyTorch
  * TensorFlow
* Matlab

Publications
============

<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
