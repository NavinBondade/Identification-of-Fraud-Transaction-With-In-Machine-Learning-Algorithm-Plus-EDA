# Identification of Fraud Transaction With 14 Machine Learning Algorithm
<p align="center">
</p>
<img src="https://www.bluefin.com/wp-content/uploads/2020/10/fraudulent-credit-card-transactions.jpg" width="970" height="520">
<p> Because of the massive rise in the use of digital payment systems for transferring money, the risk of fraud transitions has also increased. Here in this project, I have done extensive research on identifying fraud transactions using machine learning algorithms. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Wordcloud</li>
</ul>
<h2>Data Analysis</h2>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/blob/main/Pictures%20and%20Graphs/Distribution%20of%20Transaction%20Type.png">
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Amount%20Histogram.png">
</p><br>
<h2>Target Class Distribution</h2>
<p>Here zero stands for not a fraud transaction and one stands for a fraud transaction.</p>
<p align="center"> 
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Distribution%20of%20Target%20Variable.png">
</p><br> 
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Distribution%20Of%20Target%20Variable%20In%20Percentage.png">
</p><br> 
<h2>Machine Learning Algorithms</h2>   
<h3>Random Forest Classifier</h3>
<p>
A random forest classifier is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. It is basically a set of decision trees from a randomly selected subset of the training set and then It collects the votes from different decision trees to decide the final prediction. In the random forest classifier, we got the test accuracy of 84.15%.
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Random%20Forest%20Classifier%20CM.png">
</p>    
<h3>Decision Tree Classifier</h3>
<p>
The decision tree classifier is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. In this algorithm, there are two nodes, which are the decision node and the leaf node. Decision nodes are used to make any decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not contain any further branches. In the decision tree classifier, we got the test accuracy of 84.15%. 
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Decision%20Tree%20Classifier%20CM.png">
</p>    
<h3>Extra Tree Classifier</h3>
<p>
The extra tree classifier is a type of ensemble learning technique that aggregates the results of multiple de-correlated decision trees collected in a forest to output its classification result. In concept, it is very similar to a Random Forest Classifier and only differs from it in the manner of construction of the decision trees in the forest. The algorithm works by creating a large number of unpruned decision trees from the training dataset. The predictions are made by using majority voting in the case of classification. In the extra tree classifier, we got the test accuracy of 84.11%.
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Extra%20Tree%20Classifier%20CM.png">
</p>    
<h3>Support Vector Machine</h3>
<p>
In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is the number of features you have) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well. In the support vector machine classifier, we got the test accuracy of 76.51%.  
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/SVM%20Test%20CM.png">
</p> 
<h3>Nu-Support Vector Classification</h3>
<p>
The nu-support vector classifier (Nu-SVC) is similar to the SVC with the only difference being that the nu-SVC classifier has a nu parameter to control the number of support vectors. The parameter nu is an upper bound on the fraction of margin errors and a lower bound of the fraction of support vectors relative to the total number of training examples. In the nu support vector machine classifier, we got the test accuracy of 77.57%.   
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Nu-Support%20Vector%20CM.png">
</p> 
<h3>Linear SVC</h3>
<p>
The linear support vector classifier (SVC) method applies a linear kernel function to perform classification and it performs well with a large number of samples. If we compare it with the SVC model, the Linear SVC has additional parameters such as penalty normalization which applies 'L1' or 'L2', and loss function. The kernel method can not be changed in linear SVC, because it is based on the kernel linear method. In the linear support vector machine classifier, we got the test accuracy of 90.04%.   
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Linear%20Support%20Vector%20CM.png">
</p> 
<h3>Passive Aggressive Classifier</h3>
<p>
The passive-aggressive classifier is an online-learning algorithm. In online machine learning algorithms, the input data comes in sequential order and the machine learning model is updated step-by-step, as opposed to batch learning, where the entire training dataset is used at once. This is very useful in situations where there is a huge amount of data and it is computationally infeasible to train the entire dataset because of the sheer size of the data. We can simply say that an online-learning algorithm will get a training example, update the classifier, and then throw away the example. In the passive-aggressive classifier, we got the test accuracy of 80.08%.     
</p>  
<p align="center">  
<img src="https://raw.githubusercontent.com/NavinBondade/Identification-of-Fraud-Transaction-With-9-ML-Algorithm/main/Pictures%20and%20Graphs/Passive%20Aggressive%20Classifier%20CM.png">
</p> 
<h3>BernoulliNB</h3>
<p>
</p>  
<p align="center">  
<img src="">
</p> 
<h3>Gradient Boosting Classifier</h3>
<h3>Linear Discriminant Analysis</h3>
<h3>Bagging Classifier</h3>
<h3>K-Neighbors Classifier</h3>
<h3>Naive Bayes</h3>
<h3>Neural Network</h3>








