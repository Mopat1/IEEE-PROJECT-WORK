Problem Statement
 To create a Sentiment Analysis on Movie Reviews using LSTM. 
This project will label a review as positive or negative according to the reviews given.


INSTRUCTION TO RUN THE CODE

1. open the SECTION-2(TASK1).ipynb Notebook
2. On  TOP LEFT user will see an option to open the code on google colab(OPEN IN GOOGLE COLAB) . click on it
3. Wait for the notebook to open completely
4. SCROLL ALL THE WAY DOWN TO THE LAST BLOCK OF CODE
5. RUN THE LAST BLOCK OF CODE
6. PLEASE WAIT FOR THE CODE TO EXECUTE COMPLETELY 
7. AFTER EXECUTION THE USER WILL SEE THE INTERFACE OF SENTIMENT ANALYSIS ON MOVIE REVEIEW
8. DIFFERENT REVIEWS WILL SHOW DIFFERENT OUTPUT

APPROACH


This code is for sentiment analysis on movie reviews using  utilizes LSTM layers to capture sequential dependencies in text. The key steps in the process include:

Loading the Pre-trained Model: The model architecture and weights are loaded from a saved HDF5 file (model.h5). This model has been trained on text data for classifying reviews as either positive or negative.

Tokenization: A previously trained tokenizer (tokenizer.pkl) is used to convert the input review text into a sequence of integers, where each integer represents a word's index in the tokenizer's vocabulary.

Padding Sequences: The text sequence is padded to a fixed length (200 words) to ensure uniform input size for the model, as LSTMs require input of the same dimension.

Prediction: The model predicts the sentiment based on the processed input. A threshold of 0.5 is used to classify the sentiment—values greater than 0.5 are classified as positive, while those below are negative.

The use of tokenization and padding ensures that any review can be fed into the model, and the LSTM layers handle the sequential nature of the text, enabling effective sentiment prediction.
   




 
