# BSCS17005_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Dataset for Tuning Experiments
https://drive.google.com/drive/u/1/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR?authuser=1

# Dataset for Focal Loss Experiments
https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view

# Trained Weights
https://drive.google.com/open?id=11xqMvR-M-pU3qhFaZmnBU-lvzkGIY7Ss

# ResNet-18 (Fully Connected Layers Only)
Validation Accuracy: 83%
 
Test Accuracy: 89%

F1 Score: 0.898

# VGG-16 (Fully Connected Layers Only)
Validation Accuracy: 88%
 
Test Accuracy: 93%

F1 Score: 0.947

# ResNet-18 (All Layers)
Validation Accuracy: 87.6%
 
Test Accuracy: 93.7%

F1 Score: 0.941

# VGG-16 (All Layers)
Validation Accuracy: 91.1%

Test Accuracy: 96.3%

F1 Score: 0.97

This experiment yielded the best results:

![Confusion Matrices](/figure/1.png)
![Loss and Accuracy Curves](/figure/2.png)
![Well Classified and Badly Classified Images](/figure/3.png)

# VGG-16 (with Focal Loss)
Best Validation Accuracy: 90.7%

F1 Scores: [0.25, 0.95, 0.89]

![Training Confusion Matrices](/figure/4.png)
![Validation Confusion Matrices](/figure/5.png)
![Loss and Accuracy Curves](/figure/6.png)
