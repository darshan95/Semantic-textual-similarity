Semantic-textual-similarity
===========================
Aim: To find the type of semantic similarity given two similar sentences
Implemented using neural network(pybrain) and word2vec.
Training data is taken from semeval task2 2015 : http://alt.qcri.org/semeval2015/task2/

Need to install word2vec tool, pybrain

the codes are in word2vecall/scripts
the code for :
    conversion of words to vector : 'w2vtrain.py' (To run: 'python w2vtrain.py [data]')
    reading and parsing the data  : 'readsim.py' (To run: 'python readsim.py ../../data/trainTask22015/STSint.input.headlines.sent1.txt ../../data/trainTask22015/STSint.input.headlines.sent2.txt ../../data/trainTask22015/STSint.input.images.sent1.chunk.txt ../../data/trainTask22015/STSint.input.images.sent2.chunk.txt ../../data/trainTask22015/STSint.gs.headlines.wa')
    building the neural network and testing : 'class.py' (To run: 'python class.py')

Contributors: Darshan Agarwal, Ravi Chandra
