# fake_job-Prediction
Scammers post job openings online (via advertisements, employment sites, and social media), in newspapers, and even on television and radio, much like real companies do. They claim to have a job for you, but all they really want is your money and private data.
A machine learning model called Fake-Job-Predictor is built on Python and employs methods such as the Naive Bayes and Decision tree classifier algorithms to determine if a job posting is authentic or fraudulent.

### Libraries Used

* Numpy
* Pandas
* matplotlib
* Imbalanced-learn
* Natural Language Toolkit
* Multinomial Naive Bayes (scikit-learn)
* Decision tree classifier (scikit-learn)

## Dataset Analysis
The Employment Scam Aegean Dataset (EMSCAD), which is used in the model, is available [here.](https://www.kaggle.com/recruitment-scam/amruthjithrajvr)

### Visualizing dataset based on location 

<p align="center">
  <img width="460" height="300" src="img1.PNG">
</p>

### Visualizing dataset based on Experience

<p align="center">
  <img width="460" height="300" src="img2.PNG">
</p>

## Model Assessment 

### The Naive Bayes Method 
In the first method, the category text data was analyzed using Multinomial Naive Bayes, one of the most widely used supervised learning classifiers. <br>
The accuracy of classification is 0.8980769230769231. <br>

### Decision Tree Classifier
The second method made use of a decision tree classifier, which divides the input space into regions in order to classify inputs. 
The accuracy of classification is 0.8173076923076923.


