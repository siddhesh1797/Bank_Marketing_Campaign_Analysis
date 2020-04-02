# Bank_Marketing_Campaign_Analysis

Analyzed the prior marketing campaigns of a Portuguese Bank using various ML techniques like Logistic Regression, Random Forests,Decision Trees, XG Boost, KNN and SVC and predicted if the user will buy the Bank’s term deposit or not

### Dataset:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.

Source- [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014

Link- http://archive.ics.uci.edu/ml/datasets/bank+marketing

### Model Building & Comparison:
We've used quite a few models to check which fits best on our data. Models used are –

• Logistic Regression • Random Forest Classifier • Decision Tree Classifier • k-NN Classifier • SVC • XGBoost Classifier

Since this is binary classification problem, we use the following metrics:

Confusion matrix - For getting a better clarity of the no of correct/incorrect predictions by the model

ROC-AUC - It considers the rank of the output probabilities and intuitively measures the likelihood that model can distinguish between a positive point and a negative point. (Note: ROC-AUC is typically used for binary classification only). We will use AUC to select the best model.
