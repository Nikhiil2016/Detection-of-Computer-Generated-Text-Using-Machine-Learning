# Detection of Computer-Generated Text Using Machine Learning

##  Overview

This project focuses on building a supervised machine learning model to classify whether a given piece of text is human-written or AI-generated. 

With the rapid advancement of generative AI systems, detecting synthetic content has become increasingly important for academic integrity, journalism, cybersecurity, and content verification systems.

This project demonstrates applied Natural Language Processing (NLP), feature engineering, and classification modeling using Python.

---

##  Objective

- Preprocess and clean raw textual data  
- Extract meaningful linguistic features  
- Train and compare multiple classification models in both sentence level and paragraph level with and without stopwords
- Evaluate model performance using standard metrics   

---

##  Dataset

The dataset consists of:

- Human-written text samples  
- AI-generated text samples  

Data preprocessing steps included:
- Lowercasing  
- Removing punctuation  
- Tokenization  
- Stopword removal  
- Lemmatization  

---

##  Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK / SpaCy  
- Matplotlib  

---

##  Methodology

###  Text Preprocessing
- Cleaned and normalized text data  
- Tokenized sentences into words  
- Removed stopwords  
- Applied lemmatization  

###  Feature Engineering
- TF-IDF Vectorization  
- Word2vec Vectorization

###  Model Development
The following supervised learning models were implemented:

- Multinomial Naive Bayes Theorem
- Support Vector Machines
- AdaBoost Classifier  
- Random Forest Classifier
- XgBoost Classifier
- Gradient Boosting Classifier

###  Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

##  Results

The trained models successfully identified distinguishing linguistic patterns between human-written and AI-generated content.

Key observations:

- Random Forest Classifier combined with Word2Vec Vectorization acheived highest accuracy with 93%
- The experiments conducted with stopwords have a higher accuracy compared with accuracies of experiments conducted without stopwords. 

##  Future Improvements

- Implement deep learning models (LSTM, Transformer-based models)
- Expand dataset size for improved generalization
- Deploy model as a web application or REST API
