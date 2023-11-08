# binary-classification-nn-from-scratch

This is a simple deep neural network built from scratch without the help of deep learning frameworks in order, for me, to get a better understanding of how a neural network works. And then it is implemented for image classification on a dataset of cat and non-cat images.

There are serious problems with the L-layer Model as the accuracy is only 34%. My guess is that there is something wrong with my linear_activation_backward() function (or perhaps really bad choices of hyperparameters). Hopefully, I will fix this problem soon. Apologies! Howerever, the 2-layer Model can achieve an accuracy of 72% or so.