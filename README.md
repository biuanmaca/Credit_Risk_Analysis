# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis is to analyze the loan data stored in the CSV and using various methods of supervised machine learning, develop a predictive model which can
determine potential bad debt.

## Results

This analysis performs a variety of models as follows:

* Naive Random Oversampling:  The naive random oversampling model resulted in a balanced accuracy of 64%.  The precision was 99% and the recall was 66%.
![image](https://user-images.githubusercontent.com/91292960/151738916-2b305d6d-c184-4cf4-9102-459a92f080e4.png)
 
* SMOTE Oversampling:  The SMOTE oversampling model resulted in a balanced accuracy of 63%.  The precision was 99% and the recal was 64%.
![image](https://user-images.githubusercontent.com/91292960/151739133-1c4aa6be-e5ee-48f7-9b1c-a1c46a89cc87.png)

* Cluster Centroids Undersampling:  The cluster centroids undersampling model resulted in a balanced accuracy of 52%.  The precision was 99% and the recall was 46%.
![image](https://user-images.githubusercontent.com/91292960/151739265-f7075493-2621-4383-b17a-71067707e1f8.png)

* SMOTEEN Over-Undersampling:  The SMOTEEN combination sampling model resulted in a balanced accuracy of 65%.  The precision was 99% and the recall was 57%.
![image](https://user-images.githubusercontent.com/91292960/151739414-dab14896-116f-4bfb-a44b-5f4507203c15.png)

* Balanced Random Forest:  The balanced random forest ensemble model resulted in a balanced accuracy of 77%.  The precision was 99% and the recall was 66%.
![image](https://user-images.githubusercontent.com/91292960/151739587-69c733b6-78a7-400d-96d2-519a06f95673.png)

* Easy Ensemble AdaBoost Classifier:  The easy ensemble AdaBoost classifier model resulted in a balanced accuracy of 93%.  The precision was 99% and the recall was 94%
![image](https://user-images.githubusercontent.com/91292960/151739749-82361d80-b2f6-46a6-960f-d42f1395f7f2.png)
  
## Summary
Overall, the oversampling models faired better than the undersampling model and the combined sampling model faired better than either over- or undersampling alone. 
That said, none of those models produced adequate results, showing balanced accuracy percentages in the 60s.  The balanced random forest model was a significant improvement, giving us a balanced accuracy percentage of 77%.  It was the easy ensemble AdaBoost classifier model, however, that clearly performed best with a balanced accuracy of 93%.
Both the precision and the recall for that model are 99% and 94% respectively suggesting this model would deliver strong positive performance and accurately predict potential
bad debt.
