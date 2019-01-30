# 911-Priority-Classification
Priority Classification of Baltimore 911 Service Requests.

Dataset link :  https://data.baltimorecity.gov/Public-Safety/911-Police-Calls-for-Service/xviu-ezkt
Worked on Sample Dataset of 100 Thousand Rows.

Source / Primary Dataset Shape : 4.16 million+ instances * 8 attributes
Filtered / Secondary Dataset Shape : 1.13 million+ instances * 8 attributes

Target Classes = [1,2,3,4,5,6]
Emergency : 1 | 
High : 2 |
Medium : 3 |
Low : 4 |
Non-Emergency : 5 |
Out of Service : 6 

Algorithms used:

 K Nearest Neighbour : 
 Acuracy : 0.8249591 |
 Classes Identified : [2 3 4 5]
 
 Gradient Boost Classifier : 
 Accuracy : 0.9426568011700938 |
 Classes Identified : [1 2 3 4 5 6]
 
 Random Forest Classifier : 
 Accuracy : 0.9367202959648971 |
 Classes Identified : [2 3 4 5]
 
 Decision Tree, CART : 
 Accuracy : 0.9179643809687689 |
 Classes Identified : [1 2 3 4 5 6]
 
 Decision Tree, C50 : 
 Accuracy : 0.9183945625053773 |
 Classes Identified : [1 2 3 4 5 6]
 
 Bernoulli Naive Bayes : 
 Accuracy : 0.9496257420631506 |
 Classes Identified : [2 3 4 5]
 
 Gaussian Naive Bayes : 
 Accuracy : 0.6327110040437064 |
 Classes Identified : [1 2 3 4 5 6]
