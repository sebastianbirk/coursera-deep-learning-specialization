# Coursera Deep Learning Specialization

## Description
This repository contains all source code as well as notes that I have produced while working through the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) of Andrew Ng on Coursera.

## Contents
| File / folder                         | Description 
|-----------------------------------|-----------------------------------------------------------------
|`neural-networks-and-deep-learning`| This folder contains the source code as well as notes for the "Neural Networks and Deep Learning" course. <br><br> **The source code includes:** <ul><li>A Jupyter notebook for numpy basics.</li><li>A Jupyter notebook for building a logistic regression model as NN with numpy.</li><li>A Jupyter notebook for building a 3-layer NN with numpy to classify different generated datasets.</li><li>A Jupyter notebook for building a multilayer NN with numpy to classify images into cat and non-cat images.</li></ul> <br> **Key concepts covered in this course are:** <ul><li>Understand the major trends driving the rise of deep learning.</li><li>Be able to explain how deep learning is applied to supervised learning.</li><li>Understand what are the major categories of models (such as CNNs and RNNs), and when they should be applied.</li><li>Be able to recognize the basics of when deep learning will (or will not) work well.</li><li>Build a logistic regression model, structured as a shallow neural network.</li><li>Implement the main steps of an ML algorithm, including making predictions, derivative computation, and gradient descent.</li><li>Implement computationally efficient, highly vectorized, versions of models.</li><li>Understand how to compute derivatives for logistic regression, using a backpropagation mindset.</li><li>Become familiar with Python and Numpy.</li><li>Work with iPython Notebooks.</li><li>Be able to implement vectorization across multiple training examples.</li><li>Understand hidden units and hidden layers.</li><li>Be able to apply a variety of activation functions in a neural network.</li><li>Build your first forward and backward propagation with a hidden layer.</li><li>Apply random initialization to your neural network.</li><li>Become fluent with Deep Learning notations and Neural Network Representations.</li><li>Build and train a neural network with one hidden layer.</li><li>See deep neural networks as successive blocks put one after each other.</li><li>Build and train a deep L-layer Neural Network.</li><li>Analyze matrix and vector dimensions to check neural network implementations.</li><li>Understand how to use a cache to pass information from forward propagation to back propagation.</li><li>Understand the role of hyperparameters in deep learning.</li></ul>
|`improving-dnns-with-hyperparameter-tuning-regularization-and-optimization`| This folder contains the source code as well as notes for the "Improving DNNs with Hyperparameter Tuning, Regularization and Optimization" course. <br><br> **The source code includes:** <ul><li>A Jupyter notebook for weight initialization in numpy.</li><li>A Jupyter notebook for L2 and dropout regularization in numpy.</li><li>A Jupyter notebook for gradient checking.</li><li>A Jupyter notebook for comparison of different optimizers.</li><li>A Jupyter notebook containing a tensorflow tutorial.</li></ul> <br> **Key concepts covered in this course are:** <ul><li>Recall that different types of initializations lead to different results.</li><li>Recognize the importance of initialization in complex neural networks.</li><li>Recognize the difference between train/dev/test sets.</li><li>Diagnose the bias and variance issues in your model.</li><li>Learn when and how to use regularization methods such as dropout or L2 regularization.</li><li>Understand experimental issues in deep learning such as Vanishing or Exploding gradients and learn how to deal with them.</li><li>Use gradient checking to verify the correctness of your backpropagation implementation.</li><li>Remember different optimization methods such as (Stochastic) Gradient Descent, Momentum, RMSProp and Adam.</li><li>Use random minibatches to accelerate the convergence and improve the optimization.</li><li>Know the benefits of learning rate decay and apply it to your optimization.</li><li>Master the process of hyperparameter tuning.</li></ul>
|`structuring-machine-learning-projects`| This folder contains the notes for the "Structuring Machine Learning Projects" course. There were no coding exercises in this course.
|`convolutional-neural-networks`| This folder contains the source code as well as notes for the "Convolutional Neural Networks" course. This includes juypter notebooks for building a convnet in numpy, for building a convnet with tensorflow, for a keras tutorial and for face recognition.
|`sequence-models`| This folder contains the source code as well as notes for the "Sequence Models" course. This includes jupyter notebooks for jazz improvisation with a Keras LSTM,
|`README.md`                        | This README file.
|`dlspec_environment.yml`           | The conda environment to run all Jupyter Notebooks. 

## Installing the Conda Environment and Using it in Jupyter Notebook

### Two environments are available
| ENVIRONMENT_NAME | FILE_NAME |
| npdlspec | npdlspec.yml |
| tfdlspec | tfdlspec.yml |

### Install instructions
1. `conda env create -f [FILE_NAME]`
2. `conda activate [ENVIRONMENT_NAME]`
3. `python -m ipykernel install --user --name=[ENVIRONMENT_NAME]`
4. Change kernel to [ENVIRONMENT_NAME] in Jupyter Notebook (see screenshot)
![image](https://user-images.githubusercontent.com/34235961/90600791-78517f00-e1f7-11ea-84f8-9990b82e94d4.png)


