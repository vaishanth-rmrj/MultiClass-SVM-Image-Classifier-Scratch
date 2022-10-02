# MultiClass-SVM-Image_Classifier-Scratch
Coding the SVM algorithm from scratch to classify images from CIFAR-10 datasets.

## What is image classification?

Imagine the classical example: You are given a set of images each of which either depicts a cat or a dog. Instead of labeling the pictures all on your own, you want to use an algorithm to do the work for you: It "looks" at the whole picture and outputs probabilities for each of the classes it was trained on.

This is usually made possible through training neural networks, which we describe in more detail in other articles. (Note: There are other techniques but they do not play a role in practice due to performance.) As in other applications of supervised learning, the network is fed with a sufficient training data – namely labeled images of cats and dogs.

What happens in between the image and output is somewhat obscure and we are going into greater detail in other posts. But in simple terms, most networks break down the image into abstract shapes and colors, which are used to form a hypothesis regarding the image's content.


### Image Classification Techniques

1. K Nearest Neighbor
2. Support Vector Machines
3. Artificial Neural Networks
4. Convolutional Neural Networks

### Image Classification with Support Vector Machines

Generally, Support Vector Machines(SVM) is considered to be a classification approach but it can be employed in both types of classification and regression problems. It can easily handle multiple continuous and categorical variables. SVM constructs a hyperplane in multidimensional space to separate different classes. SVM generates optimal hyperplane in an iterative manner, which is used to minimize an error. The core idea of SVM is to find a maximum marginal hyperplane(MMH) that best divides the dataset into classes.


#### The working in a little more detail is as follows

SVM is a very good algorithm for doing classification. It’s a supervised learning algorithm that is mainly used to classify data into different classes. SVM trains on a set of label data. The main advantage of SVM is that it can be used for both classification and regression problems. SVM draws a decision boundary which is a hyperplane between any two classes in order to separate them or classify them. SVM  also used in Object Detection and image classification.

Here, I am going to use the Cats & Dogs dataset for doing Classification using SVM. You can collect the dataset from here. It’s a binary classification problem, but Support Vector Machine can also be used for multiclass classification problems.
