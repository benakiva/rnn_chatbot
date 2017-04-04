#Tensorflow Chatbot Trained on Cornell Movie Dialogue dataset


Overview
============
In this demo code, we implement Tensorflows [Sequence to Sequence](https://www.tensorflow.org/versions/r0.12/tutorials/seq2seq/index.html) model to train a chatbot on the [Cornell Movie Dialogue dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html). After training for a few hours, the bot is able to hold a fun conversation. This project is part of my experiments in Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models for a closed domain chatbot, for instance for a Technical Customer Support or Insurance Company's Customer Service Call Centre.


Dependencies
============
* numpy
* scipy 
* six
* tensorflow (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``


Credits
===========
Credit for the vast majority of code here goes to [suriyadeepan](https://github.com/suriyadeepan). I've merely created a wrapper to get people started. 
