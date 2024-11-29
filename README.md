<b>Data Source:</b>
1. UCI Machine Learning repository: https://archive.ics.uci.edu/dataset/222/bank+marketing 
2. The dataset contains 41,188 rows of data; 20 input features and 1 target column 'y'

Link to notebook: https://github.com/navinbilwar/bank_campaign/blob/main/prompt_III.ipynb
 
<b>Business Objectives:</b>

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution and is a collection of the results of multiple marketing campaigns. The classification goal is to predict if the client will subscribe a term deposit (variable y).

<b>Conclusion:</b>

1. The model performance of all classifiers increased when the complete bank feature dataset is used along with hyperparameter finetuning.
2. The test accuracy of SVM is highest. However, the train time (and the compute resources) are also highest. 
3. KNN’s Train and Test accuracy scores are lowest amongst all classifiers.
4. Decision Trees train time and accuracy scores were slightly better when all the features were used along with hyperparameter fine tuning as compared to Logistic Regression.
5. However, considering how logistic regression model consistently performed well with and without hyperparameter finetuning, it appears to be the most reliable classifier without the potential of overfitting and one that can be generalized to perform well on unseen data. The training time of Logistic Regression is also comparable to Decision Tree and significantly lower than SVM. 

<b>Next steps & recommendations:</b>

Further feature engineering and hyperparameter finetuning techniques could be experimented to make the model perform even better. However, it is important to avoid overfitting and ensuring the training time & resources are optimally used.
