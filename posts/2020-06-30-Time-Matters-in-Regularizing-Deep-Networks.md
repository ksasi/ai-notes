---
aliases:
- /Deep Learning/Regularization/Data Augmentation/Weight Decay/2020/06/30/Time-Matters-in-Regularizing-Deep-Networks
categories:
- Deep Learning
- Regularization
- Data Augmentation
- Weight Decay
date: '2020-06-30'
description: Time Matters in Regularizing Deep Networks
draft: 'true'
layout: post
search_exclude: false
title: Time Matters in Regularizing Deep Networks (NeuIPS 2019)
toc: true

---

<h4 style="text-align: center;" markdown="1">
  Time Matters in Regularizing Deep Networks:
</h4>
<h5 style="text-align: center;" markdown="1">
Weight Decay and Data Augmentation Affect Early Learning Dynamics, Matter Little Near Convergence
</h5>  
<h5 style="text-align: center;" markdown="1"><i>
Aditya Golatkar, Alessandro Achille, Stefano Soatto
</i></h5>
<h6 style="text-align: center;" markdown="1"><u>
Paper Notes
</u></h6>

------

**Summary** : This paper discusses that there is a "critical period" for regularization which will affect the final performance of the neural network.This is empirically verified using ResNet-18, All-CNN networks with CIFAR-10 and CIFAR-100 datasets. Also different regularization methods such as weight decay &  data augmentation were utilised along with different learning rate schedules (exponential, piece-wise constant).



**Findings** :

* Applying weight decay and data augmentation beyound the initial critical period doesn't improve generalizatin. The initial period at which these are applied decide on the performance at asymptotes.

* Applying weight decay and data augmentation during the final phases of the training doesn't improve generalization. Infact, in certain cases this degrades performance.

* Applying weight decay and data augmentation during short window is effective if only applied during the critical period of fews epochs.

<img src="./images/Screenshot 2019-12-01 at 7.59.44 PM.png" />

<img src="./images/Screenshot 2019-12-01 at 8.00.34 PM.png" />

<img src="./images/Screenshot 2019-12-01 at 8.00.56 PM.png"/>

<img src="./images/Screenshot 2019-12-01 at 8.01.11 PM.png"/>

Following can be inferred from the above figures (Figure 1 to Figure 4) obtained from the paper

* Critical periods for regularization are independent of the data distribution
* Critical periods for regularization are independent of Batch-Normalization



**Conclusion** :  The authors in the paper showed that the transient behaviour of DNN's play important role in determining how much the networks generalize. They also determined emperically , there exists a "critical period" that matters the most for applying regularization. The results in this paper can be utilized to intelligently apply regularization during "critical periods" and turn off during other parts of the training. This can help with saving computation cost and also decrease overall training time.
