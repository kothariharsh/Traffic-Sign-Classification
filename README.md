# Traffic-Sign-Classification
The goal of this project is to implement a classifier using deep learning to predict traffic signs using Tensorflow library.
I implemented a CNN  with three layers and one fully connected layer which is inspired by the work of Yann LeCun. I used Relu as the activation function and implemented augementaion and dropout.

### Importance of the Traffic Sign Classifction problem:
Traffic signs are an integral part of our road infrastructure. Traffic sign recognition is just one of the problems
that computer vision and deep learning can solve. This model will be useful in significantly improving safety and
in the implementation of an important step on the way to autonomous driving. Being able to automatically
recognize traffic signs enables us to build “smarter cars”. The same problem can be found in other fields where
we need image recognition and some of the examples include lane recognition for smart cars, number
recognition, and a lot more.

![image](https://user-images.githubusercontent.com/27828691/127936627-edbbb6d6-a56b-4356-9ee0-9af4c03dee24.png)

The dataset is first split in test, training and validation datasets, the training set consists of 34799 images, and the validation and test set consists of 4410 and 12630 images respectively. The model that I used is inspired by the LeNet Architecture which is presented by Yann Le Cun. I have added some tweaks to that architecture to provide more accurate results and the name of the network is EdLeNet.

![image](https://user-images.githubusercontent.com/27828691/127936829-f30de8ff-22d3-42dc-86ab-f62c4a652f66.png)

The above-given images are just a small illustration of how the images look after each iteration as they are been sampled down so as to obtain the best features from them which can later be used to compare it with the testing data.

I was able to acheive 95.94% validation accuracy and 97.62% test accuracy. The model was implemented using tensorflow.
![image](https://user-images.githubusercontent.com/27828691/127936925-697467ab-4b14-4a54-bc77-a466c1e6223c.png)
![image](https://user-images.githubusercontent.com/27828691/127936957-2a80e5c7-6a42-46f5-9654-17a5baf2d049.png)

The reason for the some error is the low-resolution and also because the images are pixelated which is making it difficult to identify them. Even though I was able to overcome a lot of challenges I feel the low-resolution was difficult to completely overcome.

Resource Used:
https://towardsdatascience.com/recognizing-traffic-signs-with-over-98-accuracy-using-deep-learning-86737aedc2ab
