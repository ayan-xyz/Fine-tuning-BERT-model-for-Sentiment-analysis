# Fine-tuning-BERT-model-for-Sentiment-analysis
we will fine-tune the BERT by adding a few neural network layers on our own and freezing the actual layers of BERT architecture. The problem statement that we are taking here would be of classifying sentences into POSITIVE and NEGATIVE by using fine-tuned BERT model.  
Preparing the dataset
The sentence column has text and the label column has the sentiment of the text - 0 for negative and 1 for positive. We first load the dataset followed by, some preprocessing before tuning the model.
