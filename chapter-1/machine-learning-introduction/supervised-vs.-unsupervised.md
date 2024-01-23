---
description: >-
  This chapter will describe what supervised learning and unsupervised learning
  are.
---

# Supervised VS. Unsupervised

Given a machine learning problem, first of all, one can determine whether it is a `supervised` or `unsupervised` problem. For any machine learning problem, we start from a data set, which consists of a group of `samples`. Each sample can be represented as a tuple of `attributes`.

<mark style="background-color:purple;">Review：什么是机器学习？什么是机器学习模型？</mark>

机器学习就是让机器具备找函数的能力🧮，[机器学习模型](../../#what-is-mlm)是一个文件，在经过训练后可以识别特定类型的模式。

### <mark style="color:blue;">Supervised Learning</mark>

In a _**supervised**_ learning task, the data sample would contain a target attribute {y}y, also known as _**ground truth**_. And the task is to learn a function F, that takes the non-target attributes X and output a value that approximates the target attribute, _i.e._ ~~F(X) \approx y~~

$$
F(X)≈y
$$

The target attribute _y_ serves as a teacher to guide the learning task, since it provides a benchmark on the results of learning. Hence, the task is called supervised learning.&#x20;

{% hint style="info" %}
In the Iris data set, the _class_ attribute (category of iris flower) can serve as a target attribute. The data with a target attribute is often called "_**labeled**_" data. Based on the above definition, for the task of predicting the category of iris flower with the labeled data, one can tell that it is a supervised learning task.&#x20;
{% endhint %}



\
