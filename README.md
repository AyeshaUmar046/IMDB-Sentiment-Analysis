# IMDB-Sentiment-Analysis

Beginner-friendly sentiment analysis on IMDB movie reviews using Logistic Regression.
Includes text preprocessing, feature extraction, model training, evaluation, and predictions with visuals.


# Steps Performed  

1. **Data Loading & Extraction**

  Uploaded IMDB dataset (CSV inside ZIP).
  
     
  Extracted and loaded into Pandas dataframe.  
  

2. **Data Preprocessing**
 
   Converted labels (positive/negative → 1/0).


   Lowercased text, removed HTML tags, punctuation, and stopwords.


   Created a clean text column for analysis.
   

3. **Feature Engineering**
   
    Used **CountVectorizer** with unigrams and bigrams (max 5000 features).
   

4. **Model Training**
   
   Split data (80% training, 20% testing).
  
     
   Trained **Logistic Regression** classifier.
     

5. **Evaluation**
    
    Accuracy score.

    
   Classification report (precision, recall, f1-score).

   
    Confusion matrix visualization.
   

6. **Predictions**

    Function to predict sentiment of new reviews.

    
    Tested on custom example sentences.  


##  Visuals 


### Confusion Matrix  

<img width="667" height="569" alt="confusion matrix" src="https://github.com/user-attachments/assets/49568133-d5c1-4f46-ae02-276acf016325" />



## Key Insights  

Logistic Regression achieved high accuracy on test data.  


Most misclassifications occurred between slightly positive/negative reviews.  


Text preprocessing (removing stopwords, cleaning) improved performance.  


## Tech Stack 

 **Python**
 

**Pandas, NumPy**


**Scikit-learn**

 
  **Matplotlib**  


##  How to Use  

Upload `IMDB Dataset.csv.zip` in Google Colab.


  
 Run the notebook cells step by step.

 

Try the prediction function with your own movie reviews.  



