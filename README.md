# [WWITS] Machine Learning final project

This is the final project in Wildau Welcome IT School. Author - Mykyta Bobkov

## Introduction

In this project I applied and compared classification models by using data “[Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)”.

![dataset_head](img/dataset_head.png)

The task was to use PCA model for , but by analyzing the dataset we can see that we cannot apply PCA due to the evenly distributed data. 
The solution was to convert this multiclassification problem into binary classification.  I defined a bottle of wine as ‘good quality' if it had a quality score of 7 or higher, and if it had a score of less than 7, it was deemed ‘bad quality’. 

I compared Random Forest Classifier with Gaussian Naive Bayes and with K Neighbors Classifier.

## Result
You can see results in classification score reports and confusion matrixes of each classifier.
### 1. Random Forest Classifier
![rf_cl_cf_mx](img/rf_cl_cf_mx.png)
![rf_cl_report](img/rf_cl_report.png)
### 2. Gaussian Naive Bayes
![GausNB_cf_mx](img/GausNB_cf_mx.png)
![GausNB_report](img/GausNB_report.png)
### 3. K Neighbors Classifier
![neig_cl_cf_mx](img/neig_cl_cf_mx.png)
![neig_cl_report](img/neig_cl_report.png)


## Try by yourself!

To install this project you need to enter in a terminal:

```bash
git clone https://gitlab.com/mykyta.bobkov/wwits_bobkov.git
```
**important**  - make sure that you installed all of the necessary libraries:
 
```bash
pip install -r requirements.txt
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
