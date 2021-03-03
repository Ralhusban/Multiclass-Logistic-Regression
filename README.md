# Multiclass-Logistic-Regression from scratch

This is an expansion of my older post dealing with the 2-class Logistic Regression Problem. I implement the same logic with a multiclass problem using the full Iris dataset. As you will note the main difference is that we don't use the Sigmoid function anymore and replace it with the Softmax function. During the model training, yhe Softmax function is designed to maximize the values of the correctly predicted labels and at the same time to minimize the values of the wrong labels.

This example will also teach you how to plot the cost function, which is useful to visualize if your model is learning correctly or not.

As in the previous example, I heavily use Numpy arrays to mimimize the use of for-loops.

You are free to re-use my code however, please provide a reference to it if you're publishing it anywhere else.

If any parts of the code is unclear, please let me know and I'll do my best to answer your query.
Happy learning!
