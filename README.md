 The goal is to generate automatic text summarization for the given input which is a
difficult task.

➢ The main objective of the text summarization model is to understand where important
information lies in the input to generate text summarization.

➢ Problems:
1. Rare words
2. Less frequently used words
3. Model accepts only limited amount of tokens(also called words in input text)
   
➢ Solution:
1.Transfer model with point generator layer(uses frequency information for each
word-solves the problem of rare words)
2. Hybrid approach(both abstractive and extractive (to include more important
information in the generated text summarization)
