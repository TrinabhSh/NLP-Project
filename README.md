
# NATURAL  LANGUAGE PROCESSING PROJECT  *Reviews Dataset*

![Spam Detection with Natural Language Processing - Part 3 | Blog](https://dimensionless.in/wp-content/uploads/2018/10/OyGx.gif)

## ABOUT THE DATASET

-   Product reviews dataset with 2 columns and 10,000 rows.
    
-   The columns Include Ratings and Reviews.


## INSERTING NECESSARY LIBRARIES

 - Inserting all the necessary libraries for the working of the codes.

## DATA CLEANSING

 We type the 1st function for cleaning the reviews text into better understandable text by:

- Tokenizing the words

- Removing the stopwords.

- Stemming the words.

- Removing the numbers.

## CALCULATING THE SENTIMENT SCORES
- Importing the Positive and Negative Words Dictionaries through Opinion Lexicon Library.  

- Typing 2nd function which inputs +1 for each positive word, -1 for each negative word and 0 if none.

- Returning or giving the average between sum of all the words in a list (after converting it into +1,-1, 0) and total number of words in the list.

- Typing the 3rd function which inputs different categories for different number.

## CATEGORIZING THE SENTIMENT SCORES

- ‘Positive’ for sentiment score over 0.

- ‘Negative’ for sentiment score below 0.

- ‘Positive’ for sentiment score equal to 0.

## VECTORIZING

- Applying Count Vectorizer to convert text to numerical data in terms of how many times it is appearing.

 - Applying Vectorizer to X train and X test.

## LABEL ENCODING

- Applying Label Encoder which takes a categorical column and converts it to numerical values.

- Applying Label Encoder on Y train and Y test.

## TRAINING THE MODEL AFTER CATEGORIZING

- Applying Logistic Regression to predict the probability of a categorical dependent variable.

- In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) if the array is positive or 0 (no, failure, etc.) if the array is negative.

## MODEL’S ACCURACY

Model’s Accuracy is 94%

## CONFUSION MATRIX

- Applying Confusion Matrix to see total number of true positive, false positive, false negative and true negative.

- Converting Confusion Matrix into Heatmap which tells:

True Positive (top left) – 333

False Positive (top right) – 163

False Negative (bottom left) – 20

True Negative (bottom right) – 248

- The most frequency is in True Negative.

## CLUSTERING

- KMeans Clustering to group similar kinds of items in form of clusters.

- Number of clusters chosen are 3

## WORDCLOUD FOR CLEANSED TEXT
 - **Wordclouds can be seen in the ppt file.** 
 - Through these wordclouds we can see which words are coming the most from the size of it.
 
- The bigger the size of word in the wordclouds the more it is coming in the reviews.







