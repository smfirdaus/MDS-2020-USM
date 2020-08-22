[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/smfirdaus/MDS-2020-USM/master?urlpath=lab)

# MDS-2020-USM (Improv #1)
Machine learning experiment utilizing ultrasonic flow meter (USM) diagnostics to classify the USM health state.

Upon completion of this experiment/proect research, I've thought of the following improvisation:

1. EDA: uses of Counter library to summarize the distribution
Sampling: SMOTE oversampling for multi-class imbalanced classification
Resource: https://machinelearningmastery.com/multi-class-imbalanced-classification/

2. The whole process load/train/test/validate: use Pipeline and new functions to simplify whole experiment (currently generate separate experiment for LDA and baseline cases) into 1 experiment file

3. Hyperparameter tuning:
-Cost-sensitive learning e.g. class-weight for RF
Source: https://machinelearningmastery.com/cost-sensitive-learning-for-imbalanced-classification/ 

-ROC curve & precision-recall curve : threshold-tuning to map probabilities to class label (default threshold is 0.5).
Source: https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/ 



backlink to ResearchGate: https://www.researchgate.net/project/Performance-Analysis-of-Machine-Learning-Classification-for-Ultrasonic-Flow-Meter
