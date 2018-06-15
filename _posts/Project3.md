# Learning Supervised Classification

## Predicting the Presence of Debt Sweep Covenant in Corporate Loan Contracts

In this project I tried to predict if the corporate loan contracts have debt sweep covenant provision. The learning objectives of this project were to get familiar with different supervised classification methods and making a flask app as a way to communicate the results to the audience. 

Covenants are terms in a loan contracts that limit certain activities that firm should do or should not do during the life time of their loan to protect the lenders. Debt sweep covenants is the term that prohibit the firms from issuing new debt (Completely or partially) while they are repaying their loan. 


## Data 
I got data on corporate loan charachtristics and firm charachtristics from these databases:
1) DealScan Database
2) Compustat
3) Thomson-Reuters 13F Filing
4) CRSP
My final sample had 8473 observations where 2843 of them were loan contracts without debt sweep covenants and 5630 of them were loan contracts with debt sweep covenants.

## Finding the model with highest precision
To achieve the learning objectives of this project, I tries different methods for classification and tried to optimaze them based on the precision power of the models. The methods that I used were KNN, logistic regression, SVM with different kernels, decision tree, random forest and naive Bayse. The model that gave me the best results was SVM with rbf kernel. With this model, the precison is 95% and the accuracy is 94%. You can see the results in the confusion matrix below. Also you can see the ROC curves for top 3 models in the emage below. 
 

![alt_text](https://github.com/mymnazari/mymnazari.github.io/blob/master/images/p3_1.png)
![alt_text](https://github.com/mymnazari/mymnazari.github.io/blob/master/images/p3_2.png)





