Part 3: Deep nets, Iris classification, and MNIST
======

Before we get going: are there any questions from yesterday?

Did anyone try to implement XOR? How did it go?

Have you watched the 3B1B-videos? What did you think of them? (Also little tangent: how do like them compared to our videos?)

For the first part of the day we will expand on the notion of neural networks from yesterday and look at deep NNs. 

## Deep Networks and Tensorflow

To get an intuition about DNNs, check out this page (might look a bit weird on firefox): [link](https://playground.tensorflow.org)

Then, we will look at the [Iris classification problem](https://en.wikipedia.org/wiki/Iris_flower_data_set). [Here's](https://github.com/schlenga/ML_Workshop/blob/master/Code/Iris_Classification.ipynb) the notebook.

## MNIST

We are going to learn a pretty state of the art MNIST-classifier. Warning: half-hour break necessary while the machine is trained.

![Convo](Convolution.gif)
Convolutional neural networks use the idea that images are structured and possess a hierarchy. They scan little blocks of the image instead of the image as a whole.

![MaxPool](maxPool.png)
Afterwards typically a "vote" takes place and only the most important feature per block is kept.

**Let's try it live!**