This GitHub repository contains Job_Tweets.cvs as the dataset that has been analyzed, a folder of of all data visualizations, and 3 python notebooks:

1. Job_Tweets_EDA.ipynb                   
* contains data preprocessing                                             
* application of explanatory data analysis of the dataset                                

2. Job_Tweets_TextBlob_VADER_Flair.ipynb 
* contains data preprocessing                                             
* application of textblob, VADER, Flair for sentiment analysis            

3. Job_Tweets_BERT_DistilBERT.ipynb
* contains data preprocessing                                             
* application of BERT and DistilBERT transformers for sentiment analysis  


FUTURE WORK:

For future work and recommendation, the application of the improvement such as  proper training and testing, exploration through hyperparameter tuning, and discovering the imbalance of the dataset are needed as well as a dataset from a more reliable source where proper background can be determined. Other than that, exploring more sentiment analysis tools and packages are recommended to analyze different results produced. Next, deeper exploration of the texts in the dataset to determine what kind of text preprocesses need to occur, for example, look into the first few rows of the given sentences in the dataset and determine if the sentence has symbols or URL links that need to be removed. Lastly, it is encouraged to find a dataset that is given a groundtruth so that the evaluations of models can be determined.
