# Credit_Risk_Analysis-

## Project Overview

The project is based using six different machine learning models to determine if a loan based on the data provided was considered high-risk or low risk.

## Results

1) ) Naive Random Oversampling

- Balanced Accuracy Score was 0.6438
- For high-risk loans, the precision and recall were 0.01 and 0.69, respectively. For low-risk loans, the precision and recall were 1.00 and 0.59, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/02c021d4d9bd02074ba78b42ef579642514f0f5e/Naive%20Random%20Oversampling.png)

2) SMOTE Oversampling

- Balanced Accuracy Score was 0.6628
- For high-risk loans, the precision and recall were 0.01 and 0.63, respectively. For low-risk loans, the precision and recall were 1.00 and 0.69, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/dd72b1f2ff4f7fbf994e94843c13028b6d3dce44/SMOTE%20Oversampling.png)

3)Undersamplings via Cluster Centroids

- Balanced Accuracy Score was 0.5442
- For high-risk loans, the precision and recall were 0.01 and 0.69, respectively. For low-risk loans, the precision and recall were 1.00 and 0.40, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/7fc5e3fa57c75fe2e9181d56000b9baab258fb50/Undersampling%20Via%20Cluster%20Centroids.png)

4)SMOTEEN Sampling

- Balanced Accuracy Score was 0.6748
- For high-risk loans, the precision and recall were 0.01 and 0.76, respectively. For low-risk loans, the precision and recall were 1.00 and 0.59, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/05ba5f6a38ba31c1fddf4f33d650e9c96d3eab6d/SMOTEEN%20Sampling.png)

5)Balanced Random Forest Classifier

- Balanced Accuracy Score was 0.7885
- For high-risk loans, the precision and recall were 0.03 and 0.70, respectively. For low-risk loans, the precision and recall were 1.00 and 0.87, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/783bdc90620824efca8da51b9ed0003b1e39123c/Balanced%20Random%20Forest%20Classifier.png)

6)Easy Ensemble AdaBoost Classifier

- Balanced Accuracy Score was 0.93166
- For high-risk loans, the precision and recall were 0.09 and 0.92, respectively. For low-risk loans, the precision and recall were 1.00 and 0.94, respectively.

![image](https://github.com/Dibarra11/Credit_Risk_Analysis-/blob/f206325db417af3ca70fa61ba583cc1f975209e4/Easy%20Ensemble%20AdaBosst%20Classifier.png)

## Summary

The Combination (Over and Under) Sampling showed a better-balanced accuracy score - about 68% (against random oversampling at 65%, SMOTE oversampling at 66%, and undersampling at 64.4%). However, the Easy ensemble classifier model got a higher balanced accuracy score (93%) than the balanced random forest classifier (79%). Thus both classification models performed better accuracy scores than the sampling models. F1 score is highest for Easy Ensemble AdaBoost Classifier - 97%. All the models show much more false-positive over true-positive results, which means a lot of customers' credit cards will be restricted for no reason. These models are unsuitable for commercial use, and further consideration/processing should be done in case the model was partially used in the decision-making process.

