# Twitter-Sentiment-Analysis
## About Dataset: <br/>
The dataset is obtained from Kaggle website. This twitter sentiment dataset contains 1,600,000 tweets extracted using the twitter api. The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment. <br/>

It contains the following 6 fields: <br/>
- target: the polarity of the tweet <br/>
- ids: The id of the tweet <br/>
- date: the date of the tweet <br/>
- flag: The query. If there is no query, then this value is NO_QUERY <br/>
- user: the user that tweeted <br/>
- text: the text of the tweet <br/>

### Exploratory Data Analysis (EDA):
Here EDA is done for the number of words and most commonly used words for positive and negative tweets. EDA is also done using ***WordCloud*** for positives and negatives.

## Word2Vec
A neural network is a series of algorithms that tries to recognize the underlying relationships in a dataset through a process that imitates the way the human brain operates. <br/> 
***Word2vec*** is a two-layer neural network that processes text by classifying the words into vectors. In Word2Vec each word is mapped to a unique vector and are summed to result in the final vector for any number of words. By using this method the relationship between the words can be easily found. Here, the sentiment analyser model is trained using Word2Vec method. 
