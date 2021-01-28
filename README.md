# Credit Risk Analysis

## OVERVIEW OF ANALYSIS

Using a provided credit card dataset, various resampling models were used to access credit risk.

### Algorithms Used
- RandomOverSampler 
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier 
- EasyEnsembleClassifier

---

## RESULTS

### Balanced Accuracy, Precision, and Recall Scores for each algorithm
- **RandomOverSampler**
    
    Balanced Accuracy Score: **0.65**

    ![RandomOverSampler Acc Score](images/RandomOverSampler_bac.png)

    Preicision: **0.99**

    Recall: **0.61**

    ![RandomOverSampler Report](images/RandomOverSampler_report.png)

- **SMOTE**
    
    Balanced Accuracy Score: **0.66**

    ![SMOTE Acc Score](images/SMOTE_bac.png)

    Preicision: **0.99**

    Recall: **0.69**

    ![SMOTE Report](images/SMOTE_report.png)

- **ClusterCentroids**
    
    Balanced Accuracy Score: **0.64**

    ![ClusterCentroids Acc Score](images/ClusterCentroids_bac.png)

    Preicision: **0.99**

    Recall: **0.42**

    ![ClusterCentroids Report](images/ClusterCentroids_report.png)

- **SMOTEENN**
    
    Balanced Accuracy Score: **0.58**

    ![SMOTEENN Acc Score](images/SMOTEENN_bac.png)

    Preicision: **0.99**

    Recall: **0.57**

    ![SMOTEENN Report](images/SMOTEENN_report.png)

- **BalancedRandomForestClassifier**
    
    Balanced Accuracy Score: **0.77**

    ![BalancedRandomForestClassifier Acc Score](images/BalancedRandomForestClassifier_bac.png)

    Preicision: **0.99**

    Recall: **0.87**

    ![BalancedRandomForestClassifier Report](images/BalancedRandomForestClassifier_report.png) 

- **EasyEnsembleClassifier**
    
    Balanced Accuracy Score: **0.93**

    ![EasyEnsembleClassifier Acc Score](images/EasyEnsembleClassifier_bac.png)

    Preicision: **0.99**

    Recall: **0.94**

    ![EasyEnsembleClassifier Report](images/EasyEnsembleClassifier_report.png) 

---

## SUMMARY

In conclusion, it can be said that the ensemble classifiers vastly outperformed their more basic counterparts in both accuracy and recall scores. All models returned 99% precision, as the dataset was extremely lopsided towards low-risk applications.

The EasyEnsembleClassifier model returned the best scores, and therefore would be the recommended model to use going forward.
