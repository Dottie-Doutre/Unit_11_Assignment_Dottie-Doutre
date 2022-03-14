# Unit 11 - Risky Business

## Assignment by Dorothy Doutre 

![image_add](images/credit-risk.jpg)

## Assigment Summary:

For this assignment we are tasked with building and evaluate several machine learning mdels to predict credit risks using data from peer-to-peer lending services.

Credit risk is seen inherently as an imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans).

To counter this issue we employ different techniques for training and evaluating models with imbalanced classes. 

This is done utilising the following techniques:

### Resampling:

```
Split the Data into Training and Testing.
Data Pre-Processing.
Simple Losgistic Regrression.
Oversampling (Naive Random Oversampling and SMOTE).
Undersampling (ClusterCentroids function).
Combination Sampling (Over and Under).
```

![image_add](images/image1.PNG)
Example (above) imbalanced classification report results for SMOTE oversampling model.
### Ensemble Learning:

```
Split the Data into Training and Testing.
Data Pre-Processing.
Balanced Random Forest Classifier.
Easy Ensemble Classifier.
```

![image_add](images/image2.PNG)
Example (above) imbalanced classification report results for Easy Ensemble Classifier model.

### Technologies used:
- GitBash
- Python
- Jupyter-lab (mlenv environment)
- VS Code

---

## Assignment findings:
### Credit Risk - Resampling

**1. Which model had the best balanced accuracy score?**

Multiple models - Naive Random Oversampling, SMOTE and Undersampling had the same and best accuracy score of 0.9946414201183431.

**2. Which model had the best recall score?**

All models had the best (avg) recall score of 0.99.

**3. Which model had the best geometric mean score?**

The SMOTE and Combination models are tied with the geo score of 0.99.

### Credit Risk - Ensemble

**1. Which model had the best balanced accuracy score?**

The Easy Ensemble Classifier model had the best balanced accuracy score of 0.9316600714093861, beating the Balanced Random Forest Classifier model by roughly 0.16.

**2. Which model had the best recall score?**

The Easy Ensemble Classifier model had the best recall score of 0.94 (avg) compared to the Balanced Random Forest Classifier model at 0.90.

**3. Which model had the best geometric mean score?**

The Easy Ensemble Classifier model had the best geo score of 0.93 (avg) compared to the Balanced Random Forest Classifier model at 0.75.

**4. What are the top three features?**

i. (0.06862801182224613, 'total_rec_prncp')

ii. (0.06038649619780159, 'total_rec_int')

iii. (0.05905244774386602, 'total_pymnt')

