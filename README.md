# DASC-5420-Project--Phishing-URL-Prediction

Due to advancement in internet and cloud technology, people are making more online purchase 
and transactions. This growth has leads to unauthorize access of user’s sensitive information. 
Phishing attack is one of the tricks through which cyber criminals fool people into clicking 
malicious link or handing over their personal and important information.  Therefore, it is necessary 
to develop some tools whih will detect phishing URL.

I have developed various machine learning models to detect fake URL using Logistic Regression, Ridge and Lasso 
technique for feature selection, Random Forest, Decision tree and Artificial Neural Network.

Data Link: https://www.kaggle.com/datasets/shashwatwork/phishing-dataset-for-machine-learning

Approach:

First loaded dataset using R and performed pre-processing steps.

Then experimented with Machine Learning Algorithms.
* Dataset is splitted into train and test data and models got trained on train data and evaluated on test data.
* Fitted Logistic Regression Model.
* To deal with multicollinearity, applied Ridge and Lasso technique.
* Used Decision tree and Random Forest Algorithm.
* Applied Artificial Neural Network, to build a model.
* Finall compared all models on the basis of accuracy.

So, now we can detect the phishing and legitimate URL by using the developed machine learning tools.
