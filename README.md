# BSCS17005_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Dataset for Tuning Experiments
https://drive.google.com/drive/u/1/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR?authuser=1

# Dataset for Focal Loss Experiments
https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view

# Trained Weights
https://drive.google.com/open?id=11xqMvR-M-pU3qhFaZmnBU-lvzkGIY7Ss

# VGG-16 (FC Only)
Validation Accuracy: 88%

Training Confusion Matrix:
[[4048, 871],
 [506, 6575]]
 
Validation Confusion Matrix:
[[515, 100],
 [75, 810]]
 
Testing Confusion Matrix:
[[542, 73],
 [23, 862]]
 
Test Accuracy: 93%
F1 Score: 0.947

# ResNet-18 (FC Only)
Validation Accuracy: 83%

Training Confusion Matrix:
[[3690, 1229],
 [839, 6242]]
 
Validation Confusion Matrix:
[[463, 152],
 [121, 764]]
 
Testing Confusion Matrix:
[[505, 110],
 [74, 811]]
 
Test Accuracy: 89%
F1 Score: 0.898

# VGG-16 (Entire)
Validation Accuracy: 91.1%

Training Confusion Matrix:
[[4109, 810],
 [233, 6848]]
 
Validation Confusion Matrix:
[[516, 99],
 [42, 843]]
 
Testing Confusion Matrix:
[[568, 47],
 [8, 877]]
 
Test Accuracy: 96.3%
F1 Score: 0.97

# ResNet-18 (Entire)
Validation Accuracy: 87.6%

Training Confusion Matrix:
[[4079, 840],
 [593, 6488]]
 
Validation Confusion Matrix:
[[529, 86],
 [85, 800]]
 
Testing Confusion Matrix:
[[554, 61],
 [44, 841]]
 
Test Accuracy: 93.7%
F1 Score: 0.941

# VGG-16 (with Focal Loss)

![Training Confusion Matrices](/Results/5.1.png)
![Validation Confusion Matrices](/Results/5.2.png)
![Loss and Accuracy Curves](/Results/5.3.png)

Best Validation Accuracy: 90.7%

F1 Scores: [0.25, 0.95, 0.89]
