# LSTM_GRU
We have a database that contains a column containing news and another column containing the type of news, such as what field this news is related to.

News category:
sport
business
politics
tech
entertainment

The dataset is without missing value and the dataset is ok. In order to be able to give the text to the model, we have to normalize the texts so that the text becomes completely standard so that the model can easily handle the text.

After this step we have to tokenize the texts. Tokenization is an important step in natural language processing (NLP) because it allows us to convert unstructured textual data into a structured format that can be analyzed and processed by machine learning algorithms. Now we have to encode the labels to turn them into numbers.

LSTM and GRU:
 The embedding layer in neural networks, especially in deep learning models for natural language processing tasks, is used to transform input data (eg, words or characters) into dense vectors of fixed size. This layer essentially maps high-dimensional input data into lower-dimensional embeddings that capture semantic relationships between tokens.

The advantage of using BRNN is that it can use past and future information to predict the current time step. This can be particularly useful for tasks such as language modeling, where the meaning of a word can be affected by the words before and after it.
BRNNs can be implemented using any type of RNN architecture, such as LSTM (long-term short-term memory) or GRU (gated recurrent unit). In TensorFlow with Keras API, bidirectional layer overlay can be used to create a BRNN from any existing RNN layer.

The GRU layer is a powerful tool in deep learning for sequential data processing that offers a balance between model complexity, computational efficiency, and the ability to capture long-range dependencies in a sequence. Its gating mechanism enables effective learning and modeling of temporal patterns in sequential data.

Difference between LSTM and GRU:

An LSTM cell has three gates: an input gate, an output gate, and a forget gate. The input gate controls the amount of new information that is added to the cell state, the output gate controls the amount of information that is transferred to the next cell, and the forget gate controls the amount of information that is discarded from the cell state. .

On the other hand, a GRU cell has only two gates: an update gate and a reset gate. The update gate controls the amount of new information that is added to the cell state and the amount of old information that is retained. The reset gate controls the amount of information that is discarded from the cell state.
