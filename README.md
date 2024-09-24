# GDSC ITB
Google Developer Student Clubs (GDSC) are university-based community groups for students interested in learning and applying software development skills. They’re supported by Google, and the goal is to help students learn new technologies, collaborate on projects, and create innovative solutions to local or global problems.


# Machine Learning Projects
This repository contains my work on three machine learning tasks as part of the Google Developer Student Clubs (GDSC) Machine Learning path. The tasks cover a variety of machine learning applications, from image classification to natural language processing and research on AI.

# Task 1: Flower Classification
Description: A deep learning model built using TensorFlow/Keras to classify images of flowers into different categories. The dataset contains several flower species, and the model is trained using EfficientNet
Highlights:

Dataset: The dataset used from https://www.kaggle.com/competitions/tpu-getting-started which consist of:
1. train/*.tfrec - training samples, including labels.
2. val/*.tfrec - pre-split training samples w/ labels intended to help with checking your model's performance on TPU. The split was stratified across labels.
3. test/*.tfrec - samples without labels - you'll be predicting what classes of flowers these fall into.
4. sample_submission.csv - a sample submission file in the correct format
   
Techniques: Data augmentation, EfficientNet, and evaluation metrics (accuracy, F1-score, etc.)

# Task 2: Tweet Sentiment Analysis
Description: A Natural Language Processing (NLP) model that analyzes the sentiment of tweets, classifying them as positive, negative, or neutral. The project includes data preprocessing, tokenization, and the use of LSTM-based models for sentiment prediction.
Highlights:

Dataset: The dataset used from https://www.kaggle.com/datasets/kazanova/sentiment140 which contain:
1. target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
2. ids: The id of the tweet ( 2087)
3. date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
4. flag: The query (lyx). If there is no query, then this value is NO_QUERY.
5. user: the user that tweeted (robotickilldozr)
6. text: the text of the tweet (Lyx is cool)

Techniques: Text preprocessing, word embeddings (like Word2Vec or GloVe), and LSTM/RNN models.

# Task 3: Article on Advancements in Generative AI
Description: A research article on the latest advancements in generative AI, covering models like GPT-4, DALL·E, Stable Diffusion, and their applications in creative industries, content generation, and problem-solving.

Highlights:
Discusses about DevinAI where DevinAI is an autonomous model AI software engineer .

Link to article : https://medium.com/@hendraputra151204/devin-the-first-software-engineer-ai-cfc3b8d323ab

# How to Run the Projects
1. Download the dataset from the link that listed
2. Download or Copy Notebook from kaggle
3. Run the project and feel free to tweak the code
