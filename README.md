# Transformers-Sentiment-Analysis-Python
The repository includes a Jupyter Notebook file, "Transformers Sentiment Analysis.ipynb," which showcases the step-by-step process of the sentiment analysis task.

The notebook begins by conducting necessary package imports and checking for the availability of CUDA for GPU acceleration. It then proceeds to read a CSV file, 'Reviews.csv,' containing customer reviews. A random sample of 50% of the data is selected for further analysis.

The notebook performs data preprocessing tasks such as dropping null values, analyzing the rating distribution, and mapping sentiment labels based on the ratings. It tokenizes the reviews using the BERT tokenizer and applies truncation/padding to ensure a consistent length. The tokenized reviews are converted into PyTorch tensors.

Subsequently, the notebook conducts a train-test split to prepare the data for model training. It utilizes the BERT model for sequence classification, either with a pre-trained model or a pre-trained and saved model. The notebook sets up the optimizer, learning rate scheduler, and training loop to train the model.

The training process includes epochs, calculating training and testing losses, updating the learning rate, and saving the trained model and loss values.

The notebook visualizes the training and testing loss curves, computes the classification report, and presents the confusion matrix to evaluate the model's performance. It also calculates the accuracy score for the predictions.

Additionally, the notebook provides a sample input for further evaluation, tokenizes the sample messages, and utilizes the trained model to predict the sentiment of each message along with the confidence score.

The repository offers a comprehensive implementation of sentiment analysis using transformers, allowing users to understand the process, evaluate model performance, and make predictions on new data.
