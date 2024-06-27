# racial-bias-detection
This team project is done as part of Milestone 2 project at Master of Applied Data Science program at the University of Michigan.

Description

This project utilizes both supervised and unsupervised learning methods to analyze news articles. Supervised learning approaches, including BERT (Bidirectional Encoder Representations from Transformers), Long Short-Term Memory (LSTM), Support Vector Machines (SVM), and Stochastic Gradient Descent (SGD) with Logistic Regression, are applied to classify articles based on the presence and degree of racial bias. BERT, a cutting-edge deep learning model, is particularly adept at NLP tasks, while SVM and SGD serve as classic machine learning benchmarks for text classification.

In the unsupervised learning portion, Latent Dirichlet Allocation (LDA) with TF-IDF is used for topic modeling to uncover latent themes in the text data.  Additionally, K-means clustering with word embeddings is employed to categorize similar articles, potentially revealing patterns indicative of racial bias.

The project's main findings include the superior performance of the BERT model in supervised learning, achieving an accuracy score of 85.8% and an F1 score of 0.84. In unsupervised learning, the LDA model identified 5 distinct topics related to racial discussions in news articles, and the K-means model determined that 17 clusters best represented the data.


Structure of the repository

1. data folder - includes raw and prcoessed versions of the dataset used for training
2. notebooks folder - includes code used for EDA, data processing, model training and evaluation and charts
3. results folder - includes results of experiments and charts generated for the final report
