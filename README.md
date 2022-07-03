# Chest-X-ray-Classification
Classification of Chest X-ray images from Kaggle (Course Project)

Dataset Link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

We compare CNN models with classical machine learning models like SVM, LR, and KNN. 

We also apply different dimensionality reduction methods and different oversampling techniques. 

The result is shown in the following table.


| Algorithms and pre-processing methods | F1 | Recall | Precision | Accuracy | 
|:---:|---|:---:|:---:|:---:|
| Resnet34 | 0.9173 | 0.9385 | 0.8971 | 0.8942 | 
| Resnet18 | 0.9082 | 0.9641 | 0.8584 | 0.8782 | 
| VGG11 | 0.9014 | 0.9615 | 0.8484 | 0.8686 | 
| ROS+PCA+KNN | 0.8975 | 0.9077 | 0.853 | 0.8446 | 
| VGG16 | 0.8927 | 0.982 | 0.8183 | 0.8526 | 
| SMOTE+PCA+KNN | 0.8808 | 0.9 | 0.8624 | 0.8478 | 
| PCA+LR | 0.8753 | 0.9615 | 0.7996 | 0.8253 | 
| ROS+KPCA+KNN | 0.875 | 0.8974 | 0.8537 | 0.84 | 
| SMOTE+KPCA+KNN | 0.8728 | 0.8974 | 0.8495 | 0.8365 | 
| ADASYN+PCA+KNN | 0.869 | 0.8846 | 0.854 | 0.8333 | 
| ROS+PCA+LR | 0.8682 | 0.8615 | 0.875 | 0.8365 | 
| SMOTE+PCA+LR | 0.8674 | 0.8641 | 0.8708 | 0.8349 | 
| ADASYN+KPCA+KNN | 0.8671 | 0.8615 | 0.8727 | 0.8349 | 
| SMOTE+KPCA+LR | 0.8651 | 0.9205 | 0.8159 | 0.8205 | 
| KPCA+LR | 0.8646 | 0.9333 | 0.8053 | 0.8173 | 
| ADASYN+KPCA+LR | 0.8636 | 0.9256 | 0.8094 | 0.8173 | 
| ADASYN+PCA+LR | 0.8608 | 0.8564 | 0.8653 | 0.8269 | 
| SMOTE+KPCA+SVC | 0.8549 | 0.9821 | 0.7569 | 0.7917 | 
| ADASYN+KPCA+SVC | 0.853 | 0.9744 | 0.7585 | 0.7901 | 
| ADASYN+PCA+SVC | 0.8518 | 0.9872 | 0.749 | 0.7853 | 
| KPCA+SVC | 0.8514 | 0.9846 | 0.75 | 0.7853 | 
| ROS+KPCA+SVC | 0.8514 | 0.9846 | 0.75 | 0.7853 | 
| SMOTE+PCA+SVC | 0.8505 | 0.9846 | 0.7485 | 0.7837 | 
| ROS+PCA+SVC | 0.8499 | 0.9872 | 0.7461 | 0.7821 | 
| ROS+KPCA+LR | 0.8494 | 0.8026 | 0.902 | 0.8221 | 
| KPCA+KNN | 0.8492 | 0.9744 | 0.7525 | 0.7836 | 
| PCA+KNN | 0.8463 | 0.9462 | 0.7656 | 0.7853 | 
| PCA+SVC | 0.8441 | 0.9923 | 0.7343 | 0.7708 | 
| KNN | 0.835 | 0.9795 | 0.7276 | 0.758 | 
| SVC | 0.8327 | 0.9897 | 0.7188 | 0.7516 | 
| LR | 0.828 | 0.9872 | 0.713 | 0.7436 | 



