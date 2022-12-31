# Enhancing the wifi indoor localisation using machine learning algorithm
## Introduction
Indoor localization is a very attentive research area, because GPS does not work properly for the indoor space because ther is no point-to-point contact from teh Sattelite. So, there are so many proposed methods for finding location of a person is the indoor space. Among them using wifi is very popular because now a days almost all the large places like shopping mall, airport, hospital there is wifi signal available and almost all the people are using smart phone.
Here, we used eight machine learning algorithms to enhance the performance. We used ANN, KNN, Decision tree, Naive Bayesian, ELM, SVM for this project. Additionally we use Logistic Regression, Random Forest algorithms to analyze the performance enhancement. 

### Dataset
wifi_localization.csv file is the dataset for this project.
We used dataset from the UCI machine learning library. In the dataset there are signal strengths from seven routers and for every record there is a grid in which user is. 

### How it works
We trained the machine learning algorithms with the dataset. If we give new signal strengths of the seven routers then the algorithms will predict in which grid the user is.

### Files
- **ann.pynb** - implementation of ANN algorithm
- **dt.pynb** - implementation of decision tree algorithm
- **elm.pynb** - implementation of ELM algorithm
- **knn.pynb** - implementation of KNN algorithm
- **svm.pynb** - implementation of SVM algorithm
- **randomforest.pynb** - implementation of Random Forest algorithm
- **logistic_regression.pynb** - implementation of Logistic Regrfession algorithm
- **nvb.pynb** - implemetation of Naive Bayesian algorithm
- **wifi_localization.csv** - dataset used for this project

### Performance Measurements
Among all the algorithms KNN has the heighest accuracy with 98.25% with K=3. Below table shows the performance the algorithms
| Algorithms | Performance|
|--------------|-------------|
| KNN | 98.25 |
| Naive Bayesian | 98 |
| Logistic Regression | 97.6 |
| Random Forest | 97.4 |
| SVM | 97.33 |
| Decision Tree | 91.75 |
| ELM | 85.5 |
| ANN | 25 |

### Applications
We can use wifi based indoor localization in the places like airport, healthcare system, shopping mall etc. as wifi is now a days common thing for all the plcae outside and inside and almost all the people are using smart phone for their day to day life.


