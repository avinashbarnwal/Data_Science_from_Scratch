# Data Science from Scratch with Python

Useful Links  
https://medium.freecodecamp.org/if-youre-a-developer-transitioning-into-data-science-here-are-your-best-resources-c31928b53cd1  
https://towardsdatascience.com/boosting-algorithm-xgboost-4d9ec0207d  


#AutoML Vendors  
IBM  
DataRobot  
H2O  
Oracle  
Amazon  
Microsoft  
Google  


**Computational Complexity of Supervised Learning**

Notation -  
n       - the number of training sample,   
p       - the number of features,   
n_trees - the number of trees (for methods based on various trees),   
n_sv    - the number of support vectors and   
n_li    - the number of neurons at layer  i in a neural network, we have the following approximations.  


| Algorithm                    | Classification/Regression | Training              | Prediction                  |
|------------------------------|---------------------------|-----------------------|-----------------------------|
| Decision Tree                | C+R                       | O(n^2p)               | O(p)                        |
| Random Forest                | C+R                       | O(n^2log(n)pn_trees)  | O(pntrees)                  |
| Random Forest                | R Breiman implementation  | O(n^2log(n)pn_trees)  | O(pntrees)                  |
| Random Forest                | C Breiman implementation  | O(n^2log(n)√pn_trees) | O(pntrees)                  |
| Extremly Random Trees        | C+R                       | O(npn_trees)          | O(npntrees)                 |
| Gradient Boosting            | C+R                       | O(npn_trees)          | O(pntrees)                  |
| Linear Regression            | R                         | O(p^2n+p^3)           | O(p)                        |
| SVM (Kernel)                 | C+R                       | O(n^2p+n^3)           | O(n_{sv}p)                  |
| k-Nearest Neighbours (naive) | C+R                       | −−                    | O(np)                       |
| Nearest Centroid             | C                         | O(np)                 | O(p)                        |
| Neural Network               | C+R                       | ?                     | O(pn_{l1}+n_{l1}n_{l2}+...) |
| Naive Bayes                  | C                         | O(np)                 | O(p)                        |


**Business**

- https://a16z.com/2015/09/23/16-more-metrics/

**Caliberation**
- https://machinelearningmastery.com/calibrated-classification-model-in-scikit-learn/

![Alt text](classification/caliberation_performance.png?raw=true "Title")

**Imbalanced Data**

- https://www.kaggle.com/c/ieee-fraud-detection/discussion/99982#latest-580685
- http://www.chioka.in/differences-between-roc-auc-and-pr-auc/   

**Stacking**
- https://www.kaggle.com/general/18793




