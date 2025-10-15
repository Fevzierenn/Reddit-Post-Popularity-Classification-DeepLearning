# Reddit-Post-Popularity-Classification-DeepLearning
🔍 Problem Statement
Can we predict whether a Reddit post will be popular based on its content and metadata?

This project formulates the task as a binary classification problem, where posts are labeled as popular or not popular based on upvote thresholds.

# Dataset
Source: Reddit API / Pushshift

Features used:

Post title and body

Subreddit name

Number of comments

Upvote ratio

Time of posting

 # Model Architecture
Text Embedding: TF-IDF or pretrained embeddings (e.g., GloVe)

Classifier: Deep Neural Network (DNN) with multiple dense layers

Loss Function: Binary Crossentropy

Optimizer: Adam

Evaluation Metrics: Accuracy, Precision, Recall, F1 Score

#  Results
Achieved ~XX% accuracy on test set (fill in actual value)

Confusion matrix and ROC curve visualizations included

Feature importance analysis for interpretability

#  How to Run

bash
git clone https://github.com/Fevzierenn/Reddit-Post-Popularity-Classification-DeepLearning.git
cd Reddit-Post-Popularity-Classification-DeepLearning
jupyter notebook redditPopularityDL_v2.ipynb
Make sure to install required packages:


bash
pip install -r requirements.txt


# Future Work
Incorporate transformer-based models (e.g., BERT)

Use time-series features for temporal analysis

Expand to multi-class popularity levels

#  Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

 License
This project is licensed under the MIT License.
