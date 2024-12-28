This project uses the Keras library to perform sentiment analysis on the IMDB dataset, a collection of 50,000 movie reviews labeled as positive or negative. The goal is to classify reviews based on sentiment.

The model utilizes an Embedding layer for text representation and a sequential architecture with LSTM layers for capturing context. Preprocessing includes tokenization, padding, and truncation for consistent input size.

Training is done using the Adam optimizer and binary crossentropy loss. The model achieves high accuracy on the test set.

Run train.py to train the model. Contributions are welcome under the MIT license.
