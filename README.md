# Reddit-Post-Popularity-Classification-DeepLearning
🔍 Problem Statement
Can we predict whether a Reddit post will be popular based on its content and metadata?

This project formulates the task as a binary classification problem, where posts are labeled as popular or not popular based on upvote thresholds.

# Dataset
Source: Reddit API / Pushshift

Features used:

id,title,score,upvote_ratio,num_comments,created_utc,is_self,selftext,subreddit

 # Model Architecture
Text Embedding: TF-IDF or pretrained embeddings (e.g., GloVe)

Classifier: Deep Neural Network (DNN) with multiple dense layers

Loss Function: Binary Crossentropy

Optimizer: Adam

Evaluation Metrics: Accuracy, Precision, Recall, F1 Score

#  Results
Confusion matrix and ROC curve visualizations included

Feature importance analysis for interpretability

#  How to Run

bash
<pre>
git clone https://github.com/Fevzierenn/Reddit-Post-Popularity-Classification-DeepLearning.git
cd Reddit-Post-Popularity-Classification-DeepLearning
jupyter notebook redditPopularityDL_v2.ipynb
</pre>


bash
<pre>
pip install -r requirements.txt
</pre>

# Future Work
Incorporate transformer-based models (e.g., BERT)

Use time-series features for temporal analysis


#  Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.


