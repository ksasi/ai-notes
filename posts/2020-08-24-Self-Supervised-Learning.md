---
aliases:
- /self-supervised learning/unsupervised learning/2020/08/24/Self-Supervised-Learning
categories:
- self-supervised learning
- unsupervised learning
date: '2020-08-24'
description: Basics of Self-Supervised Learning
hide: false
layout: post
search_exclude: false
title: Introduction to Self-Supervised Learning
toc: true

---

In general , if we observe the way humans learn it is evident that they don't need huge training data with explicit labels. Most of the learning is done largely in an unsupervised fashion i.e. without labels. Hence it is natural to explore if unsupervised learning can be used to improve the efficiency of different deep learning algorithms. Technically, this can mean if unsupervised learning can be used to improve or learn more interesting representations from unlabelled data.

Lets look at some of the ideas of Supervised Learning, Unsupervised Learning and Self-Supevised Learning below.



**<u>Supervised Learning</u>** : This refers to the process of training learning algorithms where an inhererent supervision is available in the data. Futher this can be defined as using labels available in the data to train learning algorithms. Classification is a common example for Supervised Learning.



**<u>Unsupervised Learning</u>** : In Unsupervised learning, there are no labels available in the data . Instead the data with features is just used by the algorithm to learn inherent structure. Clustering is an example of the algorithm that uses Unsupervised Learning.



**<u>Self-Supervised Learning</u>** : This can be thought of a subset of Unsupervised learning where in own supervision is created via pretext tasks or proxy loss. The idea and the hope is that the pretext task or proxy loss helps to learn better representations thus improving the accuracy of the learning algorithms. Further to this , it is also believed that this helps the learning algorithms generalize better.



Below are some of the advantages of using self-supervised learning:

- Availability of huge amount of unlabelled data for training
- Label once and utilize for a variety of different tasks
- Emulate the natural way in which humans/animals learn



In the next blog post, we will look at some interesting literature along with concepts that help us dive deeper into self-supervised learning.



**References** :

- [https://youtu.be/dMUes74-nYY](https://youtu.be/dMUes74-nYY)
- [https://sites.google.com/view/berkeley-cs294-158-sp20/home](https://sites.google.com/view/berkeley-cs294-158-sp20/home)
- "Lecture 7 Self-Supervised Learning" of CS294-158-SP20 course
