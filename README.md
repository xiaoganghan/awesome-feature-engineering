# awesome-feature-engineering [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/jtoy/awesome)
A curated list of feature engineering techniques for image and text machine learning.

## Table of Contents

<!-- MarkdownTOC depth=4 -->
- [Image](#image)
- [Text](#text)
- [General](#general)
<!-- /MarkdownTOC -->


<a name="image" />
## Image

### brightness, contrast, saturation
* sample implementations
1. [mxnet](https://github.com/dmlc/mxnet/blob/master/python/mxnet/image.py)

* use cases
1. [Updated! My 99.40% solution to Udacity Nanodegree project P2 (Traffic Sign Classification)](https://medium.com/@hengcherkeng/updated-my-99-40-solution-to-udacity-nanodegree-project-p2-traffic-sign-classification-5580ae5bd51f#.4hwecy9m6)

![sample](https://cdn-images-1.medium.com/max/800/1*EKInLXSKRxRqcIUdgtgJHQ.jpeg)

### spatial transformer
* sample implementations
1. [Traffic sign recognition with Torch](https://github.com/Moodstocks/gtsrb.torch)

* use cases
1. [The power of Spatial Transformer Networks](http://torch.ch/blog/2015/09/07/spatial_transformers.html)

![sample](https://raw.githubusercontent.com/moodstocks/gtsrb.torch/master/resources/epoch_evolution.gif)

### histogram equalization
* sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

* use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![input](http://navoshta.com/images/posts/traffic-signs-classification/vDGPI83pXTxsYM+yVh7kid5kid5kid5kid5kn8z8jdH5T3JkzzJkzzJkzzJkzzJ71yejLUneZIneZIneZIneZLfY3ky1p7kSZ7kSZ7kSZ7kSX6P5clYe5IneZIneZIneZIn+T2WJ2PtSZ7kSZ7kSZ7kSZ7k91iejLUneZIneZIneZIneZLfY3ky1p7kSZ7kSZ7kSZ7kSX6P5f8DZc6ez8Sy66QAAAAASUVORK5CYII=.png)

![output](http://navoshta.com/images/posts/traffic-signs-classification/fH5+9Nur3T2bA57T7e90qHNf0r6UWfH3rOyxmHv6bZXOns2m73D4XB8iwYd01kLBAKBQCAQCPw3OL7SPBAIBAKBQCDw3RHOWiAQCAQCgcAJRjhrgUAgEAgEAicY4awFAoFAIBAInGCEsxYIBAKBQCBwghHOWiAQCAQCgcAJRjhrgUAgEAgEAicYfwF7KOG348bCvwAAAABJRU5ErkJggg==.png)

### flipping
* sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

* use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![1](http://navoshta.com/images/posts/traffic-signs-classification/aug_flip_h.png)

![2](http://navoshta.com/images/posts/traffic-signs-classification/aug_flip_hv.png)

### rotation and projection
* sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

* use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![input](http://navoshta.com/images/posts/traffic-signs-classification/aug_example_orig_1.png)

![output](http://navoshta.com/images/posts/traffic-signs-classification/aug_example_aug_1.png)

### others
zooming, cropping, panning, minor color changes


<a name="text" />
## Text
### tf-idf
* sample implementations
1. [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

* use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)

### svd
* sample implementations
1. [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html)

* use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)

### PCA

### word2vec
* sample implementations
1. [gensim](http://radimrehurek.com/gensim/)

* use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)

<a name="general" />
## General
### feature engieering pipelines
* [Tips & Tricks for Feature Engineering / Applied Machine Learning](https://www.slideshare.net/HJvanVeen/feature-engineering-72376750)
### feed data to model
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)
