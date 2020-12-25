[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mzWNacITgIOnYdtAWhLOqaesZfbJB6k3?usp=sharing)

### Final Project for CSCI 6515: Machine Learning for Big Data
<b>Dalhousie University, Fall 2019</b>


For this project, we were asked to the following steps using the Reuters news corpus:
1. Cluster the documents
2. Generate a set of features for each extracted cluster separately  
3. Train a classifier for each cluster

* In the Reuters Corpus, each article has multiple topics. I explored both multi-class (just take one topic per document) and multi-label (multiple topics per document) classifications. 
* For text representation, I tried both TF-IDF and Word Embeddings and compared the final performance of each representation.
* For feature extraction, I implemented the autoencoders in paper <em>Meng, Q., Catchpoole, D., Skillicom, D., & Kennedy, P. J. (2017, May). Relational autoencoder for feature extraction. In 2017 International Joint Conference on Neural Networks (IJCNN) (pp. 364-371). IEEE</em>.
* Autoencoders and classifiers were implemented with Keras.
