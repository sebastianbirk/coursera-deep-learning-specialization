# Coursera Deep Learning Specialization

## Description
This repository contains all source code as well as notes that I have produced while working through the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) of Andrew Ng on Coursera.

## Contents
| File / folder                        | Description 
|--------------------------------------|----------------------------------------------------------------
|`01-neural-networks-and-deep-learning`| This folder contains the source code as well as notes for the "Neural Networks and Deep Learning" course. <br><br> **The source code includes:** <ul><li>A Jupyter notebook for numpy basics.</li><li>A Jupyter notebook for building a logistic regression model as a neural network with numpy.</li><li>A Jupyter notebook for building a 3-layer neural network with numpy to classify different generated datasets.</li><li>A Jupyter notebook for building deep neural networks with numpy.</li><li>A Jupyter notebook for building a deep neural network with numpy to classify images into cat and non-cat images.</li></ul> <br> **Key concepts covered in this course are:** <ul><li>Understand the major trends driving the rise of deep learning.</li><li>Be able to explain how deep learning is applied to supervised learning.</li><li>Understand what are the major categories of models (such as CNNs and RNNs), and when they should be applied.</li><li>Be able to recognize the basics of when deep learning will (or will not) work well.</li><li>Build a logistic regression model, structured as a shallow neural network.</li><li>Implement the main steps of an ML algorithm, including making predictions, derivative computation, and gradient descent.</li><li>Implement computationally efficient, highly vectorized, versions of models.</li><li>Understand how to compute derivatives for logistic regression, using a backpropagation mindset.</li><li>Become familiar with Python and Numpy.</li><li>Work with iPython Notebooks.</li><li>Be able to implement vectorization across multiple training examples.</li><li>Understand hidden units and hidden layers.</li><li>Be able to apply a variety of activation functions in a neural network.</li><li>Build your first forward and backward propagation with a hidden layer.</li><li>Apply random initialization to your neural network.</li><li>Become fluent with Deep Learning notations and Neural Network Representations.</li><li>Build and train a neural network with one hidden layer.</li><li>See deep neural networks as successive blocks put one after each other.</li><li>Build and train a deep L-layer Neural Network.</li><li>Analyze matrix and vector dimensions to check neural network implementations.</li><li>Understand how to use a cache to pass information from forward propagation to back propagation.</li><li>Understand the role of hyperparameters in deep learning.</li></ul>
|`02-improving-dnns-with-hyperparameter-tuning-regularization-and-optimization`| This folder contains the source code as well as notes for the "Improving DNNs with Hyperparameter Tuning, Regularization and Optimization" course. <br><br> **The source code includes:** <ul><li>A Jupyter notebook for weight initialization in numpy.</li><li>A Jupyter notebook for L2 and dropout regularization in numpy.</li><li>A Jupyter notebook for gradient checking.</li><li>A Jupyter notebook for comparison of different optimizers.</li><li>A Jupyter notebook containing a tensorflow tutorial.</li></ul> <br> **Key concepts covered in this course are:** <ul><li>Recall that different types of initializations lead to different results.</li><li>Recognize the importance of initialization in complex neural networks.</li><li>Recognize the difference between train/dev/test sets.</li><li>Diagnose the bias and variance issues in your model.</li><li>Learn when and how to use regularization methods such as dropout or L2 regularization.</li><li>Understand experimental issues in deep learning such as Vanishing or Exploding gradients and learn how to deal with them.</li><li>Use gradient checking to verify the correctness of your backpropagation implementation.</li><li>Remember different optimization methods such as (Stochastic) Gradient Descent, Momentum, RMSProp and Adam.</li><li>Use random minibatches to accelerate the convergence and improve the optimization.</li><li>Know the benefits of learning rate decay and apply it to your optimization.</li><li>Master the process of hyperparameter tuning.</li></ul>
|`03-structuring-machine-learning-projects`| This folder contains the notes for the "Structuring Machine Learning Projects" course. <br><br> There were no coding exercises in this course.<br><br> **Key concepts covered in this course are:** <ul><li>Understand why Machine Learning strategy is important.</li><li>Apply satisficing and optimizing metrics to set up your goal for ML projects.</li><li>Choose a correct train/dev/test split of your dataset.</li><li>Understand how to define human-level performance.</li><li>Use human-level performance to define your key priorities in ML projects.</li><li>Take the correct ML Strategic decision based on observations of performances and dataset.</li><li>Understand what multi-task learning and transfer learning are.</li><li>Recognize bias, variance and data-mismatch by looking at the performances of your algorithm on train/dev/test sets.</li></ul>
|`04-convolutional-neural-networks`| This folder contains the source code as well as notes for the "Convolutional Neural Networks" course. This includes juypter notebooks for building a convnet in numpy, for building a convnet with tensorflow, for a keras tutorial and for face recognition. <br><br> **The source code includes:** <ul><li>A Jupyter notebook for building a convolutional neural network in numpy.</li><li>A Jupyter notebook for building a convolutional neural network with tensorflow.</li><li>A Jupyter notebook containing a keras tutorial.</li><li>A Jupyter notebook for building a residual neural network with keras.</li><li>A Jupyter notebook for car detection using the YOLO algorithm.</li><li>A Jupyter notebook for art generation with neural style transfer.</li><li>A Jupyter notebook for face recognition using keras.</li></ul> **Key concepts covered in this course are:** <ul><li>Understand the convolution operation.</li><li>Understand the pooling operation.</li><li>Remember the vocabulary used in convolutional neural networks (padding, stride, filter, ...).</li><li>Build a convolutional neural network for image multi-class classification.</li><li>Understand multiple foundational papers of convolutional neural networks.</li><li>Analyze the dimensionality reduction of a volume in a very deep network.</li><li>Understand and implement a residual network.</li><li>Build a deep neural network using Keras.</li><li>Implement a skip-connection in your network.</li><li>Clone a repository from github and use transfer learning.</li><li>Understand the challenges of Object Localization, Object Detection and Landmark Finding.</li><li>Understand and implement non-max suppression.</li><li>Understand and implement intersection over union.</li><li>Understand how we label a dataset for an object detection application.</li><li>Remember the vocabulary of object detection (landmark, anchor, bounding box, grid, ...).</li><li>Discover how CNNs can be applied to multiple fields, including art generation and face recognition. Implement your own algorithm to generate art and recognize faces.</li></ul>
|`05-sequence-models`| This folder contains the source code as well as notes for the "Sequence Models" course. <br><br> **The source code includes:** <ul><li>A Jupyter notebook containing forward and backward prop of rnns and lstms in numpy.</li><li>A Jupyter notebook for building a character level language model with a rnn implemented in numpy.</li><li>A Jupyter notebook for building a jazz improvisation model with a lstm implemented in keras.</li><li>A Jupyter notebook covering glove word embeddings and operations such as cosine similarity on top of these embeddings.</li><li>A Jupyter notebook to emojify text with glove word embeddings and keras lstms.</li><li>A Jupyter notebook to do neural machine translation with attention models based on keras lstms.</li><li>A Jupyter notebook for trigger word detection with keras 1d convolutional and gru layers.</li></ul> <br> **Key concepts covered in this course are:** <ul><li>Learn about recurrent neural networks. This type of model has been proven to perform extremely well on temporal data. It has several variants including LSTMs, GRUs and Bidirectional RNNs.</li><li>Natural language processing with deep learning is an important combination. Using word vector representations and embedding layers you can train recurrent neural networks with outstanding performances in a wide variety of industries. Examples of applications are sentiment analysis, named entity recognition and machine translation.</li><li>Sequence models can be augmented using an attention mechanism. This algorithm will help your model understand where it should focus its attention given a sequence of inputs. This week, you will also learn about speech recognition and how to deal with audio data.</li></ul>
|`README.md`                        | This README file.
|`npdlspec.yml`                     | The conda environment to run all Jupyter Notebooks based on numpy. 
|`tfdlspec.yml`                     | The conda environment to run all Jupyter Notebooks based on tensorflow. 

## Installing the Conda Environment and Using it in Jupyter Notebook

### Available Environments
| ENVIRONMENT_NAME | FILE_NAME        | DESCRIPTION 
|------------------|------------------|-------------
| nndlspec         | nndlspec.yml     | Environment file for 01-neural-networks-and-deep-learning
| improvdlspec     | improvdlspec.yml | Environment file for 02-improving-dnns-with-hyperparameter-tuning-regularization-and-optimization
| cnndlspec        | cnndlspec.yml    | Environment file for 04-convolutional-neural-networks
| smdlspec         | smdlspec.yml     | Environment file for 05-sequence-models

### Installation Instructions
1. `conda env create -f [FILE_NAME]`
2. `conda activate [ENVIRONMENT_NAME]`
3. `python -m ipykernel install --user --name=[ENVIRONMENT_NAME]`
4. Change kernel to [ENVIRONMENT_NAME] in Jupyter Notebook (see screenshot)
![image](https://user-images.githubusercontent.com/34235961/90600791-78517f00-e1f7-11ea-84f8-9990b82e94d4.png)

## Sources & Links
1. Download source files from Coursera: https://www.coursera.org/learn/neural-networks-deep-learning/discussions/forums/a-1G6KlmEeeYBA47k-OCuA/threads/LTMmAazcEemTxQ73F53h-A
2. Git Large File Storage: https://git-lfs.github.com/

