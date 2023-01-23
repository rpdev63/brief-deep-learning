# CIFAR Classification
This exercise will strengthen your CNN skills by exploring the CIFAR dataset, which contains images of 10 different categories. You will also learn data augmentation techniques that helps improve a model performance.

## 🚨 Open this notebook on Google Colab 🚨  if you want


## Why Colab ?
Even quite small images and standard achitectures lead to very long computational time. This is because the neural network are (by default) run on your CPU. On the other hand, GPUs can compute large operations in parallel, which is what we are interested in as within each batch, it is theoretically possible to compute the transformation of all the images in parallel (on the contrary, the backpropagation has to be done on all the images in the same time, so no real parallelization here). Let's use Google Colab to accelerate the model convergence thanks to Google GPUs.

## What is Google Colab ?

Google Colab is nothing more than a way to have online notebooks, with the possibility to use Google GPUs. The idea here is not to use it in production (as there are some limitations) but to use Google Colab to test and prototype new algorithms. This free access to GPU allows you to accelerate the computational time. 

