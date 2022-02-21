# **Twitter Sentiment Analysis**
## **Machine Learning Algorithms Used**
* KNN
* Naive Bayes
* Logistic Regression
* Multi-layer Perceptron
* Neural Network (Kersa)

## **Data Source**
> kaggle competitions download -c comp90049-2021s2-assignment3

## **Data Cleaning**
* Check Null Values
* Convert to Lower Case
* Remove Tweet User Name
* Remove Special Characters
* Remove Stopwords (nltk.corpus.stopwords)
* Remove Punctuation
* Remove URL
* Remove Numbers
* Tokenization
* Remove Non-English Word (enchant)
* Stemming (nltk.stem.PorterStemmzer)
* Lemmatization (nltk.stem.WordNetLemmatizer)
  


## **Feature Extraction**
* Bag of Word
* TF-IDF

## **Results**
### **Different ML Algorithms Performance Table**
| Dataset | BoW (%)  |           |        |       | TF-IDF (%) |           |        |       |
| ------- | -------- | --------- | ------ | ----- | ---------- | --------- | ------ | ----- |
| Metrics | Accuracy | Precision | Recall | F1    | Accuracy   | Precision | Recall | F1    |
| KNN     | 63.67    | 65.38     | 64.18  | 64.71 | 66.34      | 67.69     | 67.43  | 67.56 |
| MNB     | 73.00    | 74.87     | 74.48  | 74.67 | 72.56      | 75.26     | 73.52  | 74.30 |
| GNB     | 58.31    | 59.73     | 64.61  | 58.23 | 58.56      | 59.86     | 64.77  | 58.49 |
| LR      | 74.14    | 75.57     | 75.90  | 75.73 | 74.26      | 75.61     | 76.08  | 75.84 |
| MLP     | 69.07    | 70.94     | 70.76  | 70.85 | 69.19      | 71.11     | 71.10  | 71.04 |
  
