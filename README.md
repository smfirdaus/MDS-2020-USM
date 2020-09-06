[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/smfirdaus/MDS-2020-USM/master?urlpath=lab)

# MDS-2020-USM (Improv #1)
Machine learning experiment utilizing ultrasonic flow meter (USM) diagnostics to classify the USM health state.

Upon completion of this experiment/proect research, I've thought of the following improvisation:

1. EDA: uses of Counter library to summarize the distribution  
Sampling: SMOTE oversampling for multi-class imbalanced classification
Resource: https://machinelearningmastery.com/multi-class-imbalanced-classification/

2. The whole process load/train/test/validate: automate and/or use new functions to simplify whole experiment (currently generate separate experiment for LDA and baseline cases) into 1 experiment file
- Pipeline to combine different models
- Grid search to find the best parameters for each model
- MLflow to record the results  
Source: https://towardsdatascience.com/how-to-fine-tune-your-machine-learning-models-with-ease-8ca62d1217b1

3. Hyperparameter tuning:  
-Cost-sensitive learning e.g. class-weight for RF  
Source: https://machinelearningmastery.com/cost-sensitive-learning-for-imbalanced-classification/ 

-ROC curve & precision-recall curve : threshold-tuning to map probabilities to class label (default threshold is 0.5).  
Source: https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/ 


## BONUS: Break the dimensionality curse by doing the followng-
1. use dimensionality reduction algorithms: Use Principal Component Analysis (PCA) or t-distributed stochastic neighbor embedding (t-SNE),
2. calculate Pearson linear correlation or Spearman non-linear correlation and remove correlated features,
3. use feature selection algorithms and keep only n-most important features,
4. get more training data if possible.  
Source: https://towardsdatascience.com/dont-get-cursed-by-dimensionality-629bca5de3a5





backlink to ResearchGate: https://www.researchgate.net/project/Performance-Analysis-of-Machine-Learning-Classification-for-Ultrasonic-Flow-Meter
