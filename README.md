# UCI HAR Activity Recognition

This project classifies human activities using smartphone sensor data from the **UCI Human Activity Recognition (HAR) dataset**. It demonstrates data preprocessing, feature scaling, machine learning model training, and evaluation.

---

## Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)  
- **Number of features:** 561 sensor measurements per sample  
- **Number of subjects:** 30  
- **Activities:** 6  
  - Walking  
  - Walking Upstairs  
  - Walking Downstairs  
  - Sitting  
  - Standing  
  - Laying  

> The dataset is split into train and test sets. All preprocessing is handled in the notebook.

## Dataset
- 561 features per sample
- 30 subjects
- 6 activities: Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying

## Model
- Logistic Regression with feature scaling
- Accuracy: 98.6%
- Confusion matrix and classification report included
