# Alzheimers-predictions-using-Patients-data

## Overview 
Alzheimer's disease (AD) is a progressive and incurable neurodegenerative disorder that affects millions of people worldwide. It is the most common cause of dementia, accounting for approximately 60-80% of all cases. The disease is characterized by the gradual loss of cognitive function, memory, and behavioral changes, leading to functional impairment and eventually, complete dependence on caregivers. Early detection and intervention are critical for improving treatment outcomes and quality of life for patients and their families. Unfortunately, current diagnostic methods rely on clinical symptoms and neuroimaging, which may not detect the disease until significant damage has already occurred.

The Alzheimer's Disease Neuroimaging Initiative (ADNI) is a large-scale, longitudinal study that collects clinical, cognitive, imaging, and genetic data from participants with AD, mild cognitive impairment (MCI), and healthy controls. This dataset provides a valuable resource for developing machine learning models to predict the onset of AD based on demographic, clinical, and genetic information.

In this data science project, we aim to develop a predictive model using machine learning algorithms to accurately identify individuals at risk of developing AD. We will explore a variety of algorithms provided by scikit-learn, including logistic regression, decision trees, random forests, support vector machines (SVMs), k-nearest neighbors (KNN), naive Bayes, and gradient boosting. We will use cross-validation and evaluation metrics such as accuracy, precision, recall, F1 score, and area under the receiver operating characteristic (ROC) curve to compare the performance of these algorithms.

The outcome of this project has the potential to aid in the early detection and diagnosis of AD, improving the lives of affected individuals and their families. Additionally, the knowledge gained from this project may inform future research into the development of effective treatments for AD.


## Results & Analysis
After implementing various machine learning algorithms on the ADNI dataset, we obtained the following results:
-	Logistic Regression: Accuracy - 69.8% 
-	Decision Tree Classifier: Accuracy - 66.7% 
-	Random Forest Classifier: Accuracy - 63.5% 
-	Support Vector Machine: Accuracy - 48.4% 
-	K-Nearest Neighbors Classifier: Accuracy - 65.9% 
-	Naive Bayes: Accuracy - 44.4% 
-	Gradient Boosting Classifier: Accuracy - 72.2%

It is evident that the Gradient Boosting Classifier algorithm outperforms all other algorithms with the highest accuracy of 72.2%. The logistic regression algorithm also performed reasonably well with an accuracy of 69.8%. On the other hand, the Naive Bayes algorithm showed the poorest performance with an accuracy of 44.4%.
The results indicate that demographic, clinical, cognitive, and genetic measures can be used to accurately predict the onset of Alzheimer's disease. Additionally, the Gradient Boosting algorithm can be used as an effective tool in the early detection and diagnosis of AD.

We further evaluated the performance of the Gradient Boosting Classifier algorithm using confusion matrix, precision, recall, and F1 score. The results are shown below:

Confusion matrix: 
[ [ 27 7 ] [ 8 27 ] ]

Precision: 0.794

Recall: 0.771

F1 score: 0.782

The results of the evaluation metrics show that the model has a relatively high precision, recall, and F1 score, indicating that it has a good overall performance in predicting the onset of AD.
