# RNNModel
Load the text data from the Sentimemt_Data folder (actually from the positive and negative subfolders) and combine the files as a single text. Let us call this combined text sentiment_text.
Build up a stateless character-RNN model for text generation, trained using sentiment_text. Train the model for 10 epochs
Build up a stateful character-RNN model for text generation, trained using sentiment_text. Train the model at least for 10 epochs
Build a function “complete_text,” which will receive two parameters: (i) a single character and (ii) temperature – and will generate text of length 100 characters.
Run “complete_text,” which will call the stateless RNN model with three different characters: “a,” “s,” and “t” with three different temperature values of your choice and provide corresponding three different outputs.
