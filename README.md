# Language-modelling-on-classical-text

Over the past few sessions, I dived into the core concepts of NLP and sequential modeling using PyTorch. I started with the basics like tokenization, case folding, removing stopwords, stemming, and lemmatization
basically all the essential text preprocessing steps. Then I moved on to traditional vectorization techniques like Bag of Words and TF-IDF to convert text into numbers for machine learning models, and used them
in a simple news classification task.

Once that clicked, I explored why plain neural nets don’t work well for sequences and how RNNs solve that by remembering past info. Then I went deeper into LSTMs... understanding gates like input, forget and output
and how they fix the vanishing gradient problem. Finally, I put all this into practice by building a Part-of-Speech tagger using an embedding layer, LSTM, and a linear output layer. This was my first proper sequence
labeling task where the model learned to tag each word in a sentence with its correct POS label.
