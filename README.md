# GENERATIVE-TEXT-MODEL

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:ABISHEK B

*INTERN ID*: CT04DH2896

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

*DESCRIPTION*: For this project, I set out to create a text generation model using LSTM (Long Short-Term Memory) networks. My goal was to build an AI system that could generate coherent text based on a seed input. Initially, I began by researching the concept of sequence modeling in deep learning and how RNNs, especially LSTMs, can be used for language generation tasks. I explored how LSTM networks are capable of maintaining memory over long sequences, making them highly suitable for natural language processing (NLP) problems like this one.To understand the theory behind the project, I watched several YouTube tutorials including Sentdex’s “Deep Learning with Python and Keras” series, “Text Generation with LSTM” by Codebasics, and videos by TensorFlow's official channel. These helped me understand the structure of RNNs, tokenization, sequence generation, and the training process involved. I also referred to online learning platforms like Coursera, where I audited parts of the "Natural Language Processing" and "Deep Learning Specialization" courses by Andrew Ng. These classes provided me with the foundational understanding of how text data is preprocessed and modeled using neural networks.I started coding by collecting a small sample corpus of sentences that covered various technical and general topics like artificial intelligence, NLP, LSTM, and deep learning. I used TensorFlow and Keras to tokenize the data and convert it into input sequences suitable for training the model. I generated n-gram sequences from each sentence to build a supervised learning dataset where each input predicts the next word. I padded the sequences to ensure uniform length and converted the output to categorical using one-hot encoding.Next, I built an LSTM model with an embedding layer, a 100-unit LSTM layer, and a dense output layer with softmax activation. I compiled the model using the categorical_crossentropy loss function and the Adam optimizer. I trained the model for 200 epochs to allow it to learn enough patterns from the limited dataset.

#OUTPUT

![Image](https://github.com/user-attachments/assets/a66be09a-6bbc-4c91-bd1d-4913addcceee)
