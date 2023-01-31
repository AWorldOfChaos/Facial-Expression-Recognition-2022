# Facial Expression Recognition

## Description

Facial expression recognition is the task of classifying the expressions on face images into various categories such as anger, fear, surprise, sadness, happiness and so on. Facial expression emotion recognition is an intuitive reflection of a person’s mental state, which contains rich emotional information, and is one of the most important forms of interpersonal communication. It can be used in various fields, including psychology. 

In this project which is a part of WiDS(Winter in Data Science) by Analytics club, IIT Bombay, We go through the basics of machine learning and deep learning as well as get a very intuitive understanding of of Convolutional Neural Networks(CNNs) from MIT recorded lecture and 3blue1brown videos. 

The later part of the project deals with implementation of what we learnt about the problem and deep learning in general. We start by implimenting Pytorch module in to solve simple problems like regression on randomly generated data and diabetes classification problem using logistic regression. Next, we impliment a fully connected Neural Net and a ConvNet on MNIST dataset which is Handwritten digit classification dataset. MNIST is kind of the most standard problem to solve using Pytorch when you start implementation for the first time. We got an accuracy of 97.09% and 99.03% using fully connected NN and a CNN architecture respectively.

For the Facial Expression Recognition problem, We implemented the architecture mentioned in 'DeXpression: Deep Convolutional Neural Network for Expression Recognition' research paper, using the Cohn-Kanade Plus (CKP) dataset, which contains the emotion classes of Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Contempt. The results of the architecture we used were supposed to be very great but we didn't reached those results using the same architecture one of the reasons being that the dataset we used was not the complete dataset used in the research paperbut was just a small portion of it. Considering the size of the dataset, we got average results which was around 65% over the test dataset. 

The final learning from the project was that, I got very comfortable with using Pytorch module. Also, the experience gained after implimenting the research paper is a very good start to understand and implement more sophisticated and scholarly research papers on topics of ML/DL. 



## CK+ Dataset

This dataset has been introduced by Lucey et al. 210 persons, aged 18 to 50, have been recorded depicting emotions. This dataset presented by contains recordings of emotions of 210 persons at the ages of 18 to 50 years. Both female and male persons are present and from different background. 81% are Euro-Americans and 13% are Afro-Americans. The images are of size 640×490 px as well 640×480 px. They are both grayscale and colored In total this set has 593 emotion-labeled sequences. The emotions consist of Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Contempt. 

The CK+ dataset is an extension of the CK dataset. It contains 327 labeled facial videos. But the dataset we are using contains just a small portion of the entire dataset.


## Architecture
![](Architecture.png "Architecture.png")

## Acknowledgments

Theory and implementation:
* [Patrick Loeber](https://www.youtube.com/@patloeber)
* [Sentdex](https://www.youtube.com/@sentdex)
* [Kartik Gokhale](https://github.com/AWorldOfChaos)
* [DeXpression: Deep Convolutional Neural Network for Expression Recognition](https://arxiv.org/pdf/1509.05371v2.pdf)
* Youtube
