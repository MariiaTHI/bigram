# bigram_model
A customer of yours is dissatissfied with the quality of the speech recognition. After a conversation
with the customer, you fond out that he dictates books. However, the speech recognition was not
built for this purpose. Accordingly, initial investigations on a book excerpt have also shown that
the language model used is not suitable. For building a better language model for the applicati-
on, you have asked your customer to provide a text from the book (see "Datasets and Resources")
In order to save costs and also to avoid problems with copyrights, your company has decided to
not use existing solutions for this project. A new program for estimating language models is now
to be programmed in Python from scratch.

Executable implementation of a baseline language model M1
Here are the general steps to implement a bigram model M1 on a PTB and WIKI dataset:
Load the dataset
Preprocess the data (tokenize, clean, etc.)
Create a vocabulary of all unique words in the dataset
Generate bigrams (pair of adjacent words) from the dataset
Compute the frequency of each bigram
Compute the probability of each bigram
Implement the bigram model M1 (with and without backoff) using the probabilities computed in the previous step
Evaluate the model using perplexity metrics.
