# Sentiment Analysis on Movie Reviews
> created by : I Gusti Ngurah Ervan Juli Ardana
----
## Description
I made this project for the ITS Internal Satria Data (Big Data Challenge) competition. The project uses machine learning to guess how people feel based on movie reviews. let's look deeper
## Workflow

1. **Import Libraries**
2. **Load the Data**
3. **Pre-process the Data**
   
   In the pre-processing stage, various approaches were employed to enhance accuracy:
   - Lowercasing
   - Removing punctuation
   - Eliminating white spaces
   - Removing numbers
   - Eliminating stop words
   - Tokenizing
   - Stemming

4. **Feature Extraction**

   Two feature extraction methods were explored: `TF*IDF` and `Ngrams`. The accuracy analysis indicated that `TF*IDF` yielded superior results.

5. **Model Development**
  
   Several models were tested, including logistic regression, Naive Bayes, Random Forest, and SVM. Based on accuracy results, logistic regression was chosen as it demonstrated the highest accuracy.

6. **Hyperparameter Tuning**

   Hyperparameter tuning was performed using gridsearchcv to optimize the logistic regression model's parameters.

7. **Test Prediction**

   After completing all these steps, the model achieved an accuracy of 0.881.


<img width="279" alt="image" src="https://github.com/NgurahErvan/Sentiment-Analysis-on-Movie-Reviews/assets/114007640/80aafc25-469b-4908-b48b-d1d0d8400e7e">
