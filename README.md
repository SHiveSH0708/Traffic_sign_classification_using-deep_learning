# Traffic_sign_classification_using-deep_learning

## Overview

A convolutional neural network for German traffic sign image classification.

## Dataset

German Traffic Sign Recognition Dataset (GTSRB) is an image classification dataset. The entire dataset can be found here (https://drive.google.com/file/d/1FnYd6jYODQEcMgMVT58CAgl4Wj601J0j/view?usp=sharing).
The images are photos of traffic signs. The images are classified into 43 classes. The training set contains 39209 labeled images and the test set contains 12630 images. Labels for the test set are not published.

## Model

ResNet-34 pretrained on ImageNet dataset, then finetuned on GTSRB dataset.

## Deep Learning Libraries

tensorflow, keras

## Metrics

The model achieved about 99% accuracy on the validation set (random 20% subset of the training dataset).

---

#### Repository by : Shivesh Gupta
