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


**Algorithm**  &nbsp;&nbsp;   **Classification/Regression**   &nbsp;&nbsp;    **Training**  &nbsp;&nbsp; **Prediction**  
Decision Tree  &nbsp;&nbsp;                C+R                                      O(n^2p)           O(p)  
Random Forest  &nbsp;&nbsp;                C+R                                      O(n^2pn_trees)    O(pntrees)  
Random Forest  &nbsp;&nbsp;                R Breiman implementation                 O(n^2pn_trees)    O(pntrees)  
Random Forest  &nbsp;&nbsp;                C Breiman implementation                 O(n^2√pn_trees)   O(pntrees)  
Extremly Random Trees   &nbsp;&nbsp;       C+R                                      O(npn_trees)      O(npntrees)    
Gradient Boosting       &nbsp;&nbsp;       C+R                                      O(npn_trees)      O(pntrees)  
Linear Regression       &nbsp;&nbsp;       R                                        O(p^2n+p^3)       O(p)    
SVM (Kernel)            &nbsp;&nbsp;       C+R                                      O(n^2p+n^3)       O(nsvp)  
k-Nearest Neighbours (naive)  &nbsp;&nbsp; C+R                                        −−              O(np)   
Nearest centroid        &nbsp;&nbsp;       C                                        O(np)             O(p)  
Neural Network          &nbsp;&nbsp;       C+R                                        ?               O(pnl1+nl1nl2+...)  
Naive Bayes             &nbsp;&nbsp;       C                                        O(np)             O(p)  

 














