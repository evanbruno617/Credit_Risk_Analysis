# Purpose
The purpose of this project is to analyze credit loans data to predict whether loans will be bad or not. 

## Analysis

### RandomOverSampling
With RandomOverSampling I obtained a balanced accuracy of 64.69% with a 1% Precision for high risk but a 69% recall score. It also has a 100% precision for low-risk individuals with a 60% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/RandomOver.png)

### SMOTE
With SMOTE I obtained a balanced accuracy of 65.25% with a 1% Precision for high risk but a 69% recall score. It also has a 100% precission for low-risk individuals with a 40% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

### Cluster Centroids
With SMOTE I obtained a balanced accuracy of 54.43% with a 1% Precision for high risk but a 62% recall score. It also has a 100% precision low-risk with a 68% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

### SMOTEEN
With SMOTEEN I obtained a balanced accuracy of 63.79% with a 1% Precision for high risk but a 70% recall score. It also has a 100% precision for low-risk individuals with a 57% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/SMOTEEN.png)

### RandomForestClassifier
With SMOTEEN I obtained a balanced accuracy of 68.3% with a 88% Precision for high risk but a 37% recall score. It also has a 100% precision for low-risk individuals with a 100% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/RandomForest.png)

### GradientBoostingClassifier
With SMOTEEN I obtained a balanced accuracy of 66.61% with a 62% Precision for high risk but a 33% recall score. It also has a 100% precision for low-risk individuals with a 100% recall score.
![image](https://github.com/evanbruno617/Credit_Risk_Analysis/blob/main/Resources/GradientBoosting.png)

---

## Summary
For RandomOverSampling, SMOTE, Cluster Centroids, and SMOTEEN they had relatively balanced accuracy scores within the mid to low 60 percent which is the amount of time the model predicts the correct outcome. However these tests produce very low precision score for high-risk invididuals of 1% with a recall score ranging from 30-70%. For low-risk individuals it had a precision score of 100% therefore being able to correctly predict low-risk individuals 100%   of the time with a recall score ranging from 40-60%. Out of the last two models RandomForestClassifier beats GradientBoostingCLassifier in every ctaegory so I will focus on this module. It has a 88% precision and 37% recall score for high-risk individuals and close to 100% for both precision and recall for low-risk individuals. I believe this is the model to be used as it more accurately predicts individuals to be high risk eliminating all of the potential low-risk individuals which could therefore increase profit instead of turning those invididuals away with a less accurate precision score. 

