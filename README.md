## A Comparative Study on Deep Learning approaches and Attention Mechanisms for Machine Comprehension on SQuAD dataset

This is the result of my Final Year Project at University. For this, I built and compared the performances of different Deep Learning approaches to Question Answering on Wikipedia articles, proving the efficacy of Attention Mechanisms in Machine Comprehension. The models were implemented using Keras and Tensorflow, using Recurrent Neural Networks and Attention. 


1. Model 1 - Word Embeddings (Baseline model)
2. Model 2 - Recurrent Neural Networks (RNNs)
3. Model 3 - RNNs with Attention Mechanisms
4. Model 4 - R-Net Model (Wang et al., 2017)

Each of these models were all applied to two different tasks: a “QA task” on the whole SQuAD dataset, and a second task, which is referred to as "OWQA task” (One Word Question Answering). For this OWQA task, only a subset of SQuAD dataset was considered, containing only one-word answers.

The models were trained and tested on a modest GPU GeForce GTX 1080, which did not allow the best performance on such a big and complex dataset.
