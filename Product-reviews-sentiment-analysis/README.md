## Product review sentiment analysis

[Competition link](https://www.kaggle.com/c/product-reviews-sentiment-analysis)

### Target
Only test dataset is given. 
So it needs to be done:
 * Parse train dataset somewhere on the internet
 * Mark raw data
 * Train model and send prediction
 
As a source of train data I've decided to use market.yandex.ru, as a side with good structure and huge amount of reviews. 
What makes it easy to parse all necessary data. But due to organizer of the competition is Yandex as well I think that there are some 
intersections in train and test data, what has brought such good result.
 
### Models
 * RussianStemmer   - as data preparation
 * CountVectorizer  - as data vaporizing
 * TfidfTransformer - as transformation of vectors
 * RidgeClassifier  - as classifier
  
### Result
 * Public leaderboard  - 100%
 * Private leaderboard - is unknown for now