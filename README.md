### About

Corresponding code to the paper "Towards Evaluating the Robustness of Neural
Networks" by Nicholas Carlini and David Wagner, at IEEE Symposium on Security &
Privacy, 2017.

Implementations of the three attack algorithms in Tensorflow. It runs correctly
on Python 3 (and probably Python 2 without many changes).

To evaluate the robustness of a neural network, create a model class with a
predict method that will run the prediction network *without softmax*.  The
model should have variables 


This code is provided under the BSD 2-Clause, Copyright 2016 to Nicholas Carlini.
