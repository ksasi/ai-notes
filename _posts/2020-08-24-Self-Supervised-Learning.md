```
title: Introduction to Self-Supervised Learning
description: "Self-Supervised Learning"
layout: post
toc: true
comments: true
hide: false
search_exclude: false
categories: [self-supervised learning, unsupervised learning]
```



In general , if we observe the way humans learn it is evident that they don't need huge number of training data with explicit labels. Most of the learning is done hugely via Unsupervised fashion i.e. without labels. Hence it is more natural to explore if Unsupervised learning can be used to improve the efficiency of learning algorithms. Technically this means that can Unsupervised learning be used to improve or learn more representations from unlabelled data.

But before we dive into self-supervised learning lets understand what is Supervised learning and Unsupervised learning.



**<u>Supervised learning</u>** : This refers to the process of training learning algorithms where an inhererent supervision is available in the data. Futher this can be defined as using labels available in the data to train learning algorithms. Classification is a common example for Supervised Learning.



**<u>Unsupervised learning</u>** : In Unsupervised learning, there are no labels available in the data . Instead the data with features is just used by the algorithm to learn inherent structure. Clustering is an example of the algorithm that uses Unsupervised Learning.



**<u>Self-Supervised Learning</u>** : This can be thought of a subset of Unsupervised learning where in own supervision is created via pretext tasks or proxy loss. The idea and the hope is that the pretext task or proxy loss helps to learn better representations thus improving the accuracy of the learning algorithms. Further to this , it is also believed that this helps the learning algorithms generalize better.



Below are the advantages of using self-supervised learning:

- Availability of huge amount of unlabelled data for training
- Label once and utilize for a variety of different tasks
- Emulate the natural way in which humans/animals learn



In the next blog post, we will look at some interesting literature along with concepts that help us dive deep into self-supervised learning.



**References** :

- https://youtu.be/dMUes74-nYY

- https://sites.google.com/view/berkeley-cs294-158-sp20/home

- "Lecture 7 Self-Supervised Learning" of CS294-158-SP20 course

  

















