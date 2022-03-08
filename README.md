# AspectBased_SentimentAnalysis_usingBERT
Working with a BERT Model for Aspect-based Sentiment Analysis using Pre-trained models from the Hugging Face Library 

These are the steps done in this project:-
1. Data Cleaning 
2. Exploratory Data Analysis
3. Model Building
4. Prediction 
5. Evaluation

### *Include a research paper submitted as a thesis project at Dublin City University 2020-2021*

## This Folder also contains all the code files related to the Practicum paper in Documentation folder.
1. Practicum Movie Dataset
In this .ipnyb file we use the Movie Reviews dataset shared in the Main page. We apply Machine Learning Algorithms i.e Naive Bayes, Logistic Regression and Support Vector Machines to the dataset to find the sentiment of a text, i.e. positive or negative.
This is part of preliminary work to understand the algorithms better and work with text data.
2. SentiHood_with_ML_algorithms
In this .ipnyb file we use the SentiHood dataset shared in the Main page which has text with 2 locations and 12 aspects. We apply Machine Learning Algorithms i.e Naive Bayes, Logistic Regression and Support Vector Machines to the dataset to find the sentiment of a text, i.e. positive, negative or none.
We use the TFIDF vectorizer and One-Hot encoding to pre-process the text and aspects.
In this we carried out the following experiments:
a. Sentiment analysis with text
b. Sentiment analysis with text + aspect
c. Sentiment analysis with text + one-hot encoded aspects
3. Sentiment_analysis_with_Huggingface_DistilBERT
This .ipnyb file also uses the SentiHood dataset shared in the Main page which has text with 2 locations and 12 aspects. We use the DistilBERT model from the Huggingface library to carry out experiments.
We find the polarity of a sentence i.e. positive, negative or none from this experiment.
4. Sentiment_analysis_using_Text_Sep_aspect
This .ipnyb file also uses the SentiHood dataset shared in the Main page which has text with 2 locations and 12 aspects. We use the DistilBERT model from the Huggingface library to carry out experiments.
We find the polarity of a sentence i.e. positive, negative or none.
In this we carried out the following experiments:
a. DistilBERT using Text [SEP] Aspect
b. DistilBERT using Text + Aspect
5. Sentiment_analysis_using_BERT_aspect_classifiers
This .ipnyb file also uses the SentiHood dataset shared in the Main page which has text with 2 locations and 12 aspects. We use the DistilBERT model from the Huggingface library to carry out experiments using aspect classification.
We get the accuracy, precision, recall and F1 score for each aspect and location in the dataset.
6. Sentiment_analysis_using_SVM_aspect_classifiers
This .ipnyb file also uses the SentiHood dataset shared in the Main page which has text with 2 locations and 12 aspects. We use the SVM model to carry out experiments for aspect classification.
We get the accuracy, precision, recall and F1 score for each aspect and location in the dataset.

