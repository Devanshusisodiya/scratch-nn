### Analysis of MLP and Regressor Performance Over Multiple Optimizers

This is a Neural Network I created from scratch to get a better understanding of the concept. I documented everything, in an easy to follow
document with bite sized chunks of the concepts that were required to build this network.

The dataset used was the **MNIST handwritten digits** dataset, and the network has the below illustrated architecture.

<img width="1342" alt="image" src="https://github.com/Devanshusisodiya/scratch-nn/assets/43195822/16a04724-4ff3-48d3-a50a-2e31be0e343b">

I trained the network using 2 different optimizers - ***Gradient Descent*** defined in `gradient_descent` function and ***Gradient Descent with Momentum*** defined in `gradient_descent_wm` function
to study whether the convergence of the network.
