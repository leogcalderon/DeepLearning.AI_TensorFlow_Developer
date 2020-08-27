# Convolutional Neural Networks in TensorFlow
*by deeplearning.ai*

In Course 2 of the deeplearning.ai TensorFlow Specialization, you will learn advanced techniques to improve the computer vision model you built in Course 1. You will explore how to work with real-world images in different shapes and sizes, visualize the journey of an image through convolutions to understand how a computer “sees” information, plot loss and accuracy, and explore strategies to prevent overfitting, including augmentation and dropout. Finally, Course 2 will introduce you to transfer learning and how learned features can be extracted from models.

## 1. Exploring a Larger Dataset
In this course you'll go deeper into using ConvNets will real-world data, and learn about techniques that you can use to improve your ConvNet performance, particularly when doing image classification!

## 2. Augmentation: A technique to avoid overfitting
You've heard the term overfitting a number of times to this point. Overfitting is simply the concept of being over specialized in training -- namely that your model is very good at classifying what it is trained for, but not so good at classifying things that it hasn't seen. In order to generalize your model more effectively, you will of course need a greater breadth of samples to train it on. That's not always possible, but a nice potential shortcut to this is Image Augmentation, where you tweak the training set to potentially increase the diversity of subjects it covers.

## 3. Transfer Learning
Building models for yourself is great, and can be very powerful. But, as you've seen, you can be limited by the data you have on hand. Not everybody has access to massive datasets or the compute power that's needed to train them effectively. Transfer learning can help solve this -- where people with models trained on large datasets train them, so that you can either use them directly, or, you can use the features that they have learned and apply them to your scenario.

## 4. Multiclass Classifications
One more thing to do before we move off of ConvNets to the next module, and that's to go beyond binary classification. Each of the examples you've done so far involved classifying one thing or another -- horse or human, cat or dog. When moving beyond binary into Categorical classification there are some coding considerations you need to take into account.
