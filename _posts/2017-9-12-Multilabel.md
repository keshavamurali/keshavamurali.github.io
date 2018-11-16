---
layout: post
title: Multi Label Classification using Deep Learning
---
[Multi Label Classification](https://en.wikipedia.org/wiki/Multi-label_classification) is a variant of Classification problems where each instance is classified into one or more than one classes. This poses an interesting challenge in the Machine Learning world, since most of the "traditional" classification algorithms are centered around the assumption that each input (training/test) instance belongs to a particular class. <br/>

Using [Deep Neural Netowrks](https://en.wikipedia.org/wiki/Deep_learning) for multi label classification is being studied for a while as of now. There has been lot of research around this area and lot of good papers have come out (You can find more information in the references below.). However, most of the deep learning methods have shown either sub-par or equivalent performance compared to traditional machine learning schemes, such as Bayessian Networks, Classifier Chains ..etc. <br/>

I have been trying to use DNNs (with one set of hidden nodes) for Multi Label Classification for an interesting Supervised Learning problem. I have a data set which are classified to single class most of the times. However, there is around 10% of the possibility where it belongs to more than one class. In such cases, the input belongs to a set of classes which is the subset of *Y* = { y<sub>1</sub>,y<sub>2</sub>,y<sub>3</sub>,y<sub>4</sub> ... } <br/>

I will share my findings and code soon.




