---
layout: post
title:  "Clustering"
date:   2018-11-13 11:24:31 +0800
author: Nikolavac
categories: Clustering 
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

在聚类任务中，训练样本的标记信息未知,无监督学习的目的是通过对无标记样本的学习来揭示未知规律

聚类试图通过将数据集合中的样本划分为不相交的子集，称为簇 _cluster_, 然而对于算法本身来说分类的结

果对应的概念是未知的，需要人为的给定具体对应的概念。

**性能度量**

聚类的性能度量也可称为有效性指标。 _Validity index_ 我们总是希望聚类的结果是簇内相似度 _intra-cluster similarity_

较高,而簇内相似度 _inter-cluster similarity_ 较低。性能度量的方法可以分为两类：

* 与标准的模型进行对比称为外部指标 _external index_
* 直接考察聚类结果而不利用其他模型的称为 _internal index_

**外部指标** 

$$ x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$