# Fraud_Detection
Fraud detection for highly skewed data
 1. Here will see how to deal with imbalanced dataset
 2. What performance metric we should choose
 3. How to deal with highly skewed dataset
 4. Perform Precision-Recall trade off
 
Conclusion:
1. When we have imbalanced dataset - like this highly skewed then Oversampling and SMOTE really helps our model in terms of F1 score
2. We should intially split our dataset and apply sampling techniques only on train set
3. We should always test our model in original test dataset which does not have samples created by us
4. We have seen that RandomForest Classifier/Extra Trees classifier has the best results among the other powerful classifier
5. We see the accuracy is not a good meteric for evaluation for imbalanced dataset
6. F1 score and Precision-recall trade off or curve is better perfoamce metric for highly skewed data
7. For RandomForest 0.67 is the threshold which gives highest F1 score of 0.8524
8. For Extra Trees 0.61 is the threshold which gives highest F1 score of 0.8524
9. We can further play around and optimize the RandomForest Classifier/Extra Tree clasifier as both gave same results
10 Sometimes Neural Network model does not perform well as compared to other ensemble models
