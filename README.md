# Twitter Personality Prediction using word embeddings and deep learning
the word embedding used need to be downloaded and put in under dataset/glove.6B
the link to download : https://nlp.stanford.edu/projects/glove/  (glove.6B.zip)


the bert model need to be downloaded , extracted and the files put in under dataset/bert
the link to download : https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip
in the bert config file change the max_position_embeddings from 512 to the length of each vector (2132 right now)