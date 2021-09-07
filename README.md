# Face-Recognition-using-CNNs
To identify an individual, the face is the focus of primary attention. The human faces represent complex, multidimensional, and meaningful visual stimulants. The human capacity to identify faces is extremely remarkable, and to infer intelligence or character from facial appearance is astounding. The ability of individuals to determine the emotional state, the subject of attention, and the intent of others are essential skills for effective social interactions, in addition to the simple ability to identify. For all these purposes, face recognition has become a field of intense focus for the vision community, and has gained a large amount of attention in the past few years. In addition, Deep Learning-based approaches have achieved major performance improvements on numerous computer vision tasks, including face recognition, with the advancement of Deep Convolutional Neural Networks.

## Problem Statement
A face recognition device/system with the input of an arbitrary image can check for the identity of different people present in the input image. In general, a facial recognition system consists of four broad modulesIdentification, Alignment, Extraction of Features, and Matching, where localization and normalization are used. We can recognize thousands of faces learned throughout our lifetime and even recognize familiar faces at a glance even after years of separation. But this skill is not useful
if there are changes in a person’s faces, due to viewing conditions, expression, aging, and distractions such as glasses, beards or changes in hair style. With this project, through comprehensive analysis and interpretation of facial image samples using state of the art deep learning methods, robust face recognition algorithms will be explored.
The prime objective is to develop a robust pipeline/model for facial image feature extraction using deep learning techniques for accurate user recognition.

## Dataset 

For the purpose of this project, we consider the LFW (Labelled Faces in the Wild) dataset, a database of face photographs designed for studying the problem of unconstrained face recognition. The data set contains more than 13,000 images of faces collected from the web. Each face has been labelled with the name of the person pictured. 1680 of the people pictured have two or more distinct photos in the data set. The only constraint on these faces is that they were detected by the Viola-Jones face detector, an outdated but powerful face detector.

## Convolutional Neural Network 

<p align="center">
  <img src="https://github.com/Vaibhav-Sachdeva/Vaibhav-Sachdeva/blob/main/Images/CNN_frame.PNG" width="600"/>
</p>
With time, advances in Computer Vision with Deep Learning have been developed and refined, predominantly by one unique algorithm, a Convolutional Neural
Network (ConvNet). A Deep Learning algorithm, Convolution Neural Network can take an input image, allocate significance (learnable weights and biases) to various aspects of the image and be able to differentiate one from the other. As compared to other classification algorithms, the pre-processing required in a ConvNet is much lower. Although filters are hand-engineered in primitive ways, but with enough experience, ConvNets have the ability to learn these features.
The ConvNet architecture is comparable to that of the neuron connectivity pattern in the human brain and was inspired by the Visual Cortex organization. Individual neurons respond only in a small area of the visual field, known as the Receptive Field, to stimuli.ConvNets are a type of feed-forward neural networks that consist of filters or kernels or neurons that have weights or parameters and biases that can be learned. Each filter takes those inputs, performs convolution and, optionally, non-linearity follows. it

