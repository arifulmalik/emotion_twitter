# emotion_twitter
This project extracts emotional attributes from the twitter posts to gain knowledge about the emotional status of the inhabitants of a particular region.
For this, we collect twitter posts that is related to covid-19 and perform a transfer learning approach to predict the emotional status of the tweet. We collect our dataset from kaggle and implement a Bert pretrained model to identify emotions on the tweets. We perform evaluation on TweetEval dataset in which our Bert model shows 80\% accuracy.

# Files in this project
- Evaluation.ipynb 
- Result.ipynb
- Data_Visualization.ipynb
- covid19_tweetes.csv
- predicted_output.csv

## Evaluation.ipynb
This notebook file is for the evaluation of our model. It will download the TweetEval dataset from huggingface. Then it will train the data using the Bert model and then evaluate the model using the test data provided by the TweetEval. Our Bert model achieves 80\% accuracy in test set. 

## Result.ipynb
This notebook is designed to predict the emotion from our collected dataset from Kaggle. The dataset file name is `covid19_tweetes.csv`. 

## Data_Visualization.ipynb
This notebook is mainly for the graph plotting on the predicted results. 

## covid19_tweets.csv
This csv file is our dataset with which we will perform emotion detection.


## predicted_output.csv
This csv file stores the result of our model with the covid19_tweetes dataset. 
