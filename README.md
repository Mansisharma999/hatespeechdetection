# hatespeechdetection
There must have been occasions when you came across a social media message whose sole purpose was to spread hate and controversy or to use abusive language on social media sites. Because the post is made up of text, NLP can help filter out such hate speech. This is one of the primary uses of NLP, known as Sentence Classification.

In this post, we will learn how to create an NLP-based Sequence Classification model that can predict if Tweets are Hate Speech, Offensive Language, or Normal.

Importing Libraries and Datasets
Python libraries make it simple for us to handle data and conduct common and sophisticated activities with a single line of code.

Pandas - This library assists in loading data frames in a 2D array format and includes many functions for performing analysis tasks in one go.
Numpy arrays are extremely quick and can execute huge computations in very little time.
Matplotlib/Seaborn/Wordcloud- This library is used for creating visualisations.
The Natural Language Tool Kit (NLTK) provides a variety of functions for processing raw textual data.
Text Preprocessing
Textual data is highly unstructured and need attention on many aspects like:

Stopwords Removal
Punctuations Removal
Stemming or Lemmatization
Although removing data means loss of information but we need to do this to make the data perfect to feed into a machine learning model.
