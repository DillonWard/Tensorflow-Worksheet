# Tensorflow Worksheet
###### *Dillon Ward - G00326756 - Emerging Technologies*
---
## Introduction
The following repository contains solutions to Tensorflow problem sheets written in Python with Jupyter Notebook for the module Emerging Technologies. The module is taught to undergraduate students at GMIT in the Department of Computer Science and Applied Physics. The lecturer is Ian McLoughlin.

## Prerequisites
* [git](https://git-scm.com/)
* [Python](https://www.python.org/downloads/)
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Anaconda](https://anaconda.org/)

## Cloning this Repository
To clone this repository and run the solutions, do the following:

```
In the command line change to a directory:
cd <directory>

Clone the repository:
https://github.com/DillonWard/Tensorflow-Worksheet

Change directory into the cloned folder:
cd <folder name>

*To ensure you're in the right folder, you can run the ls command to display all the files inside the folder. 
Files ending with 'ipynb' are Jupyter Notebook files.*

Run the program:
jupyter notebook
```

## Tensorflow
### What is Tensorflow?
[TensorFlow](https://en.wikipedia.org/wiki/TensorFlow) is an open-source software library for dataflow programming across a range of tasks. It is a symbolic math library, and also used for machine learning applications such as neural networks.

It was originally developed by the Google Brain Team within Google's Machine Intelligence research organization for machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well.

TensorFlow is cross-platform. It runs on nearly everything: GPUs and CPUs—including mobile and embedded platforms—and even tensor processing units, which are specialized hardware to do tensor math on.

### What is Tensorflow used for?
Tensorflow has an multiple uses, such as image recognition, human language, and linear models. See the [Tensorflow Tutorials](https://www.tensorflow.org/tutorials/) for more details.

### [Installation](https://stackoverflow.com/a/42129546/8394648)
```
conda create --name tensorflow python=3.6
activate tensorflow
conda install jupyter
conda install scipy
pip install tensorflow-gpu

```
## Keras
### What is Keras?
[Keras](https://keras.io/) is a neural networks programming framework written in Python that is used for simplifying of creating deep learning applicaitons. Rather than Keras providing all of the functionalities itself, it's ran on top of Tensorflow, CNTK, or Theano and adds a simplified interface.

### What is Keras used for?
Use Keras if you need a deep learning library that:

* Allows for prototyping through a user friendly interface
* Supports convolutional networks, recurrent networks, or a combination of both.
* Runs seamlessly on CPU and GPU.

### Installation
```
pip install h5py # used for saving modules
pip install keras
```

## Anaconda
### What is Anaconda?
[Anaconda](https://en.wikipedia.org/wiki/Anaconda_(Python_distribution)) is an open source distribution for Python and R programming languages, used for large-scale data processing, predictive analytics, and scientific computing, and aims to simplify package management and deployment. Anaconda aims to provide users with everything they need to get started with data science.

### Installation
To download and install Anaconda, head over to the Anaconda [Installation Section](https://conda.io/docs/user-guide/install/index.html) on their website.
* [Anaconda for Windows](https://conda.io/docs/user-guide/install/windows.html)
* [Anaconda for macOS](https://conda.io/docs/user-guide/install/macos.html)
* [Anaconda for Linux](https://conda.io/docs/user-guide/install/linux.html)

## [Worksheet](https://emerging-technologies.github.io/problems/tensorflow.html)
### 1. Use Tensorflow to create model
Use Tensorflow to create a model to predict the species of Iris from a flower’s sepal width, sepal length, petal width, and petal length.


### 2. Split the data into training and testing
Split the data set into a training set and a testing set. You should investigate the best way to do this, and list any online references used in your notebook. If you wish to, you can write some code to randomly separate the data on the fly.

### 3. Train the model
Use the testing set to train your model.

### 4. Test the model
Use the testing set to test your model, clearly calculating and displaying the error rate.

#### [Solution](https://github.com/DillonWard/Tensorflow-Worksheet/blob/master/Tensorflow-Worksheet.ipynb)

## References
* [Wikipedia - Tensorflow](https://en.wikipedia.org/wiki/TensorFlow)
* [Tensorflow Tutorials](https://www.tensorflow.org/tutorials/)
* [Keras](https://keras.io/)
* [Lynda - What is Keras?](https://www.lynda.com/Google-TensorFlow-tutorials/What-Keras/601801/642171-4.html)
* [Anaconda](https://anaconda.org/)
* [Anaconda Installation](https://anaconda.org/)
