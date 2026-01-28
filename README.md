# NLP-text-classification-project-IMDB-sentiment-analysis
This is an natural language processing based text classification project using the IMDB dataset from hugging face. 
IMDB is an leading website for finding movies and tv shows. Users can search for movies and tv shows and write positive or negative reviews. Given that an average person wastes plenty of time searching for movies that they would like, IMDB wants to recommend movies based on the users preferences. 
For this purpose, we will build an NLP based text classification model to predict user sentiments based on their past reviews. If successful, this model can help IMDB recommend movies to the users based on the preferences derived from their past reviews about movies. IMDB can benefit from this model by improving user retention and engagement.

This project was performed on Google Colab. The IMDB dataset was imported from hugging face. It contains 2 features titled text (reviews) and label (sentiments) with rows split into train, test and unsupervised sets. Training set has 25,000 rows, test set has 25,000 rows and the unsupervised set has 50,000 rows.

Steps: 

1. The IMDB movie review data was imported from hugging face.
2. The data was explored to check pre-processing requirements
3. In the preprocessing stage, the text was converted into lowercase. HTML tags, URLs, punctuation marks and stopwords were removed. Chatwords or abbreviations were converted into full form. Long form text was converted into tokens. Lemmatization was performed to convert the words to their base form to avoid repetition.
4. In the feature engineering stage, the tokens were converted back into strings. The BoW and TF-IDF vectorization was performed to create feature matrices.
