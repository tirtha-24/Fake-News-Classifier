# **Fake-News-Classifier**

### **Objective**
1. Classify the news from the dataset to fake or true news.
2. Exploratory data analysis of news
3. Selecting and building a powerful model for classification.

### **Contents**
1. Preprocessing and Cleaning.
2. Visualization from news.
3. Stemming & Vectorizing.
4. Machine learning Model Building and Selection.
5. Deep Learning- LSTM and Bidirectional LSTM.

### **Machine Learning Models**
1. Logistic regression
2. KNN
3. Decision trees.
4. Multinomial Naive Bayes.

Logistic regression gave best result. So, I hypertuned the regularization parameter and trained the model with the best hyperparameter after cross-validation, which gave nearly 99% accuracy. TF-IDF weighting was used for calculating the feautures of the input document. Features were obtained by considering both unigrams and bigrams. Top 8000 features were taken based on term frequency.

### **Deep Learning Models**
1. LSTM, nearly 97% accuracy.
2. Bidirectional LSTM, nearly 99 % accuracy.

Bidirectional LSTM and logistic regression are the winner models in this case. But, sequence models like LSTM considers the sequence information and learns the order dependency in a sentence. Thus, considering the sequence information is a mandatory criteria. Therefore, bidirectional LSTM is considered as the final model for this project.

