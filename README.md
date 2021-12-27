# ***Credit_Risk_Analysis--Module17***

## ***Overview of the analysis:***

In this Module I have been privileged to use Python-Jupyter Notebook to build and evaluate several machine learning models  ̶̶̶̶  that are: Naïve Random OverSampling, SMOTE-OverSampling, ClusterCentroids’ Undersampling, SMOTEENN’s combination of-over-and-under-sampling, and then two ensemble algorithms (Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier). I learned and applied these models for me to predict the credit risk for the unsecured personal loans that are suffered by a large number of American populations. 

Thus, I came to realization that with the help of machine learning algorithms, the credit risk is predicted which can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud.

As Machine Learning is divided into two parts: Supervised and unsupervised learnings, this module is only concentrating on the latter one (Supervised) for predicting the credit risk.

## ***Results:***

- Deliverable 1: Usage of Resampling Models to Predict Credit Risk

         Figure 1 clearly shows that the high risk loan cases has 0.01 precision value and 0.61 recall value and low risk loan cases has precision value of 1.00 and 0.68 of recal value. F1 score is in favour for low-risk with the value of 0.81. Over-all, the accuracy score is 0.644. 

         As it is already known that a low precision is indicative of a large number of false positives and a low recall is indicative of a large number of false negatives, it can be concluded that the Naïve Random OverSampling model is inefficiently able to figure of which one (from False negatives and False positives) is in greater amount regardless its accuracy score. 


<figure>
  <img src="screenshots\NaiveRndmOvrSmpling.png" width="450" height="250">
  <figcaption>Fig 1: Naïve Random OverSampling</figcaption>
</figure>



         Figure 2 shows that the high risk loan cases has 0.01 precision value and 0.64 recall value and low risk loan cases has precision value of 1.00 and 0.63 of recal value. F1 score is in favour for low-risk with the value of 0.77. Over-all, the accuracy score is 0.637. 

         As it is already known that a low precision is indicative of a large number of false positives and a low recall is indicative of a large number of false negatives, it can be concluded that the SMOTE-OverSampling model is just like the Naïve Random OverSampling model as it also is inefficiently able to figure of which one (from False negatives and False positives) is in greater amount regardless its accuracy score. 


<figure>
  <img src="screenshots\SMOTE-Oversampling.png" width="450" height="250">
  <figcaption>Fig 2: SMOTE-OverSampling</figcaption>
</figure>

         Figure 3 shows that the high risk loan cases has 0.01 precision value and 0.59 recall value and low risk loan cases has precision value of 1.00 and 0.44 of recal value. F1 score is in favour for low-risk with the value of 0.61. Over-all, the accuracy score is 0.531. 


         After seeing the results, it is concluded that there is higher number of false positives in high-risk. This false positive data could be misleading. since our recall value is lower for low-risk which means that there might be  higher number of hish-risk than calculated by the model. Hence, Undersampling has inefficient is producing realistically accepting results.  



<figure>
  <img src="screenshots\undrsampling.png" width="450" height="250">
  <figcaption>Fig 3: UnderSampling</figcaption>
</figure>



- Deliverable 2: Usage of SMOTEENN algorithm to Predict Credit Risk


<figure>
  <img src="screenshots\Combination(OverandUnder)sampling.png" width="450" height="250">
  <figcaption>Fig 4: Combination (Over and Under) sampling</figcaption>
</figure>

         Figure 4 shows that the high risk loan cases has 0.01 precision value and 0.70 recall value and low risk loan cases has precision value of 1.00 and 0.57 of recal value. F1 score is in favour for low-risk with the value of 0.73. Over-all, the accuracy score is 0.638. 

         After seeing the results, it is 
         categorically seen that we highest number of false positives in hish - risk cases. As this could be misleading data, so in order to verify this calculated result, it is noted that the recall value has lower number in favour of low-risk cases and that means there might be higher number of False negatives than calculated. hence, there might be more than the calculated cases for high-risk loan cases. 
         
         Just like the models used in the deliverable 1, this model is also agreeing with their results that were produced by Naive, Under and SMOTE-Oversampling. Hence, it is seen that the SMOTENN combo Model is a verfication of the previous models used in predicting data. SMOTENN, however, is still not efficient in producing trustworthy results.



- Deliverable 3: Usage of Ensemble Classifiers to Predict Credit Risk


<figure>
  <img src="screenshots\BalancedRandomForestClassifier.png" width="450" height="250">
  <figcaption>Fig 5: Balanced Random Forest Classifier</figcaption>
</figure>

        Figure 5 shows that the high risk loan cases has 0.72 precision value and 0.33 recall value and low risk loan cases has precision value of 1.00 and 1.00 of recal value. F1 score is in favour for low-risk with the value of 1.00. Over-all, the accuracy score is 0.996. 


         After seeing the results, it is concluded that there is reasonable number of higher-risk of false positives cases. The recall value is in favour for high risk that means that there is reasonable number of higher risk as that of calculated. Thus, this model is efficient in producing a reasonable result. 



<figure>
  <img src="screenshots\Easy-Ensemble-AdaBoost-Classifier.png" width="450" height="250">
  <figcaption>Fig 6: Easy Ensemble AdaBoost Classifier </figcaption>
</figure>

        Figure 6 shows that the high risk loan cases has 0.08 precision value and 0.91 recall value and low risk loan cases has precision value of 1.00 and 0.91 of recal value. F1 score is in favour for low-risk with the value of 0.97. Over-all, the accuracy score is 0.944. 


         After seeing the results, it is concluded that there is reasonable number of higher-risk of false positives cases. The recall value is in favour for high risk that means that there is reasonable and acceptable number of higher risk as that of calculated. Thus, this model is efficient in producing a reasonable result in the deliverable 3.


## ***Summary:***

After seeing the models' results from the respective deliverables, it is conculded that the SMOTENN (from deliverable 2) is the model that supports the models' results that were used in deliverable 1. In deliverable 3, however, the Adapost easy ensemble model is better in producing the accepatble and realistic results. 
