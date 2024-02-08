# Reverse dictionary

A regular (forward) dictionary maps words to their definitions. While a reverse dictionary takes the description of a word as input and outputs the target
word together with other semantically similar words.

<img width="785" alt="image" src="https://github.com/ada0110/reverse-dictionary/assets/64487038/caf83c2e-95e3-4e60-9b41-6e10d6b036c4">
<br/>

Reverse dictionary problem deals with mapping an input query phrase to word(s) which is/are semantically similar to it. The problem is useful both from human and machine learning system point of view. A model that’s good at solving the reverse dictionary problem can be helpful while learning new languages, and it can also be helpful in other downstream tasks like machine translation and entity linking. However, in order to solve the problem, the model would need to first learn vector representations of phrases and target words and then learn a function that maps these representations to each other. 

In this [thesis](Reverse_Dictionary_Thesis.pdf), we discuss about learning the models and vector representations of phareses and target words which can be used to solve the problem. We also discuss that current solutions are generally limited to a monolingual setting and how we can move to multilingual and cross-lingual setting for this problem.  

