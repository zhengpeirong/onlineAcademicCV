---
title: "Dakun Lai, *Peirong Zheng*, Yuchen Jiang and Yuxiang Bu, PAFNet：A Real-time Deep Learning Model for the Prediction of Paroxysmal Atrial Fibrillation Onset using Single-lead ECG"
collection: publications
excerpt: 'Submitted to *Journal of Biomedical and Health Informatics (JBHI)*, 2023. Currently waiting for the response.'
paperurl: 'http://academicpages.github.io/files/JBHI-PAF_prediction.pdf'
---
Not published yet. Submitted to the Journal of Biomedical and Health Informatics (JBHI) on 2023-04-13.

[Download paper here](http://academicpages.github.io/files/paper2.pdf)


Abstract—This study presents PAFNet, a novel real-time
deep learning model designed to predict the onset of
paroxysmal atrial fibrillation (PAF) at least 45 minutes in
advance using a single-lead electrocardiogram (ECG)
signal. Fifty ECG records from the publicly accessible PAF
prediction challenge database (AFPDB) were used to
extract RR interval sequences for the training of PAFNet,
while another thirty ECG records from the MIT-BIH Atrial
Fibrillation Database (AFDB) and the MIT-BIH Normal Sinus
Rhythm Database (NSRDB) were used for database-level
testing. Each RR interval sequence was divided into sliding
windows of size 100 and a step of 1, which were used as
input data for PAFNet. In total, 56,381 PAFN-type and 56,900
N-type RR interval segments were extracted. The proposed
PAFNet features 5 one-dimensional convolutional layers,
forming a light-weighted architecture that can
accommodate the size of sliding windows by only altering
the input layer. Employing the ten-fold cross-validation
method, PAFNet achieved an average sensitivity,
specificity, and accuracy of 97.12%, 97.77%, and 97.45%,
respectively. The promising results suggest that PAFNet
achieves high performance and offers the possibility of
providing real-time, accurate, and inexpensive clinical
tools to assist clinicians in predicting PAF events.
