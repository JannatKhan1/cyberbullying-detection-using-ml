**AIM :** To classify the comments posted on social media as harmful or non-harmful.

Process Followed:

**1. Data Collection:**
The cyberbullying detection model built is targeted for the Indian audience. Hence, we searched for the datasets which included the Indian audience. The cyberbullying comments
were obtained from Twitter, Instagram and Youtube. The scripts were classified into numerical categories. ‘0’ is considered as non-cyberbullying and ‘1’ is considered as cyberbullying. The dataset is structured.

**2. Data Preprocessing:**
Techniques used:
a. Normalization
b. Tokenization
c.  Lemmatization and Stemming:

**3. Feature Extraction:**
NLP Techniques used:
a. BoW
b. Tf-IDF

**4. Training Model:**
ML Algorithms Used:
a. Random Forest Classifier
b. Logistic Regression
c. Light GBM
d. Stochastic Gradient Descent

**Performance Summary**
 1. Performance summary of the algorithms used in our Cyberbullying Detection Model. We can see that LightGBM and Stochastic Gradient Descent have similar accuracy,recall and F1 score. However, the precision of LightGBMis more than Stochastic Gradient Descent.
![image](https://github.com/JannatKhan1/cyberbullying-detection-using-ml/assets/89721610/ba88f2ae-a576-445e-bdb8-6bb5df90df32)

2.  F-measure of all Algorithms
We know that precision helps us check how many of our correctly predicted labels are actually correct. Precision determines the cost of false positives. Recall helps us check if our predictions are actually correct. Recall is used when there is a high cost of true negatives. In order to maintain the balance of Precision and Recall, F-measure is calculated.
![image](https://github.com/JannatKhan1/cyberbullying-detection-using-ml/assets/89721610/e0495074-7e33-4e48-af6b-256ae04f378e)
