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
#### sample implementations
1. [mxnet](https://github.com/dmlc/mxnet/blob/master/python/mxnet/image.py)

#### use cases
1. [Updated! My 99.40% solution to Udacity Nanodegree project P2 (Traffic Sign Classification)](https://medium.com/@hengcherkeng/updated-my-99-40-solution-to-udacity-nanodegree-project-p2-traffic-sign-classification-5580ae5bd51f#.4hwecy9m6)

![sample](https://cdn-images-1.medium.com/max/800/1*EKInLXSKRxRqcIUdgtgJHQ.jpeg)

### spatial transformer
#### sample implementations
1. [Traffic sign recognition with Torch](https://github.com/Moodstocks/gtsrb.torch)

#### use cases
1. [The power of Spatial Transformer Networks](http://torch.ch/blog/2015/09/07/spatial_transformers.html)

![sample](https://raw.githubusercontent.com/moodstocks/gtsrb.torch/master/resources/epoch_evolution.gif)

### histogram equalization
#### sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

#### use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![input](http://navoshta.com/images/posts/traffic-signs-classification/vDGPI83pXTxsYM+yVh7kid5kid5kid5kid5kn8z8jdH5T3JkzzJkzzJkzzJkzzJ71yejLUneZIneZIneZIneZLfY3ky1p7kSZ7kSZ7kSZ7kSX6P5clYe5IneZIneZIneZIn+T2WJ2PtSZ7kSZ7kSZ7kSZ7k91iejLUneZIneZIneZIneZLfY3ky1p7kSZ7kSZ7kSZ7kSX6P5f8DZc6ez8Sy66QAAAAASUVORK5CYII=.png)

![output](http://navoshta.com/images/posts/traffic-signs-classification/fH5+9Nur3T2bA57T7e90qHNf0r6UWfH3rOyxmHv6bZXOns2m73D4XB8iwYd01kLBAKBQCAQCPw3OL7SPBAIBAKBQCDw3RHOWiAQCAQCgcAJRjhrgUAgEAgEAicY4awFAoFAIBAInGCEsxYIBAKBQCBwghHOWiAQCAQCgcAJRjhrgUAgEAgEAicYfwF7KOG348bCvwAAAABJRU5ErkJggg==.png)

### flipping
#### sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

#### use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![1](http://navoshta.com/images/posts/traffic-signs-classification/aug_flip_h.png)

![2](http://navoshta.com/images/posts/traffic-signs-classification/aug_flip_hv.png)

### rotation and projection
#### sample implementations
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

#### use cases
1. [Traffic signs classification with a convolutional network](http://navoshta.com/traffic-signs-classification/)

![input](http://navoshta.com/images/posts/traffic-signs-classification/aug_example_orig_1.png)

![output](http://navoshta.com/images/posts/traffic-signs-classification/aug_example_aug_1.png)

### others
zooming, cropping, panning, minor color changes

### Libraries
* [imgaug: Image augmentation for machine learning experiments.](https://github.com/aleju/imgaug)

![output](https://github.com/aleju/imgaug/raw/master/examples_grid.jpg?raw=true)

<a name="text" />

## Text
### stemmer
#### sample implementations
1. [nltk](http://www.nltk.org/_modules/nltk/stem/porter.html)

#### use cases
1. [Q&A With Job Salary Prediction First Prize Winner Vlad Mnih](http://blog.kaggle.com/2013/05/06/qa-with-job-salary-prediction-first-prize-winner-vlad-mnih/)


### tf-idf
#### sample implementations
1. [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

#### use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)

### svd
#### sample implementations
1. [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html)

#### use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)

### PCA

### word2vec
#### sample implementations
1. [gensim](http://radimrehurek.com/gensim/)

#### use cases
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)
2. [Do-it-yourself NLP for bot developers](https://conversations.golastmile.com/do-it-yourself-nlp-for-bot-developers-2e2da2817f3d#.9yz22bhzp) (text classification, entity recognition)

#### pipeline
* [Document Classification with scikit-learn](http://zacstewart.com/2015/04/28/document-classification-with-scikit-learn.html)
* use separate bags of words for different attributes of text

<a name="general" />
## General

#### general feature engineering

* [特征工程到底是什么？(in Chinese)](https://www.zhihu.com/question/29316149)

![input](https://pic3.zhimg.com/20e4522e6104ad71fc543cc21f402b36_b.png)

* [Image augmentation for machine learning experiments.](https://github.com/aleju/imgaug)

### feature engieering pipelines
* [Tips & Tricks for Feature Engineering / Applied Machine Learning](https://www.slideshare.net/HJvanVeen/feature-engineering-72376750)
* represent categorical features using 1-of-K encoding

### data exploration with Pandas
* [Data Wrangling with Pandas](http://nbviewer.jupyter.org/urls/gist.github.com/fonnesbeck/5850413/raw/3a9406c73365480bc58d5e75bc80f7962243ba17/2.+Data+Wrangling+with+Pandas.ipynb)
* [A Rubric for Data Wrangling and Exploration](http://nbviewer.jupyter.org/github/cs109/content/blob/master/lec_04_wrangling.ipynb)

### feed data to model
1. [Is That a Duplicate Quora Question?](https://www.linkedin.com/pulse/duplicate-quora-question-abhishek-thakur)
