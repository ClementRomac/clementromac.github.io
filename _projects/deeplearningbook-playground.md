---
title: "Deep Learning Book Playground"
excerpt: "Projects to put in practice what I've learned from the DeepLearning Book"
collection: projects
date: 2018-04-17
---

During 2018, I read the [DeepLearning Book](https://www.deeplearningbook.org/) from Ian Goodfellow, Aaron Courville and Yoshua Bengio. I wanted to put in practice what I had learned in chapters 6, 7, 8, 9 and 10 so I made three projects :
- The first one, on chapters 6, 7 and 8, was an implementation of a FeedForward Neural Network on the [notMNIST dataset](http://yaroslavvb.blogspot.com/2011/09/notmnist-dataset.html) where I tested optmization and regluarization methods.
- The second one, on chapter 9, was an implementation of a Convolution Neural Network on the same dataset than the previous one. I mainly tested to plot convolution kernels and feature maps.
- The third, on chapter 10, took the major part of my time. I wanted to apply a Recurrent Neural Network in the context of NLP and more particularly for translation. I thus tried to make a simplified version of the Google Neural Machine Translation with a Seq2Seq based on LSTM cells. I used this [tutorial](https://machinelearningmastery.com/prepare-french-english-dataset-machine-translation/) to get a clean French-to-English dataset and [this one](https://machinelearningmastery.com/develop-neural-machine-translation-system-keras/) to prepare data before entering the Neural Network. 

I used Tensorflow in Python for all the projects.

You can fin the code on this [repository](https://github.com/ClementRomac/DeepLearningBookPlayground) where there's also a [presentation](https://github.com/ClementRomac/DeepLearningBookPlayground/blob/master/Presentation.pdf) I made.