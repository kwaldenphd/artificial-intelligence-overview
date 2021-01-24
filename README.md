# Introduction to Core Concepts in Artificial Intelligence

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents

# Overview

When working in and around artificial intelligence and machine learning, the jargon and concepts can quickly become overwhelming.

This tutorial is designed to provide an overview of core concepts in artificial intelligence, with a focus on machine learning.

# Algorithms

“In mathematics and computer science, an algorithm is a finite sequence of well-defined, computer-implementable instructions, typically to solve a class of problems or to perform a computation. Algorithms are always unambiguous and are used as specifications for performing calculations, data processing, automated reasoning, and other tasks.” ([Wikipedia](https://en.wikipedia.org/wiki/Algorithm))

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_1.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_1.png?raw=true" /></a></p>

<p align="center">Image from [GeeksforGeeks](https://www.geeksforgeeks.org/introduction-to-algorithms/)</p>

A recipe used in cooking is one example of an algorithm. The ingredients list and recipe steps provide a set of conditions and a step-by-step procedure for completing or achieving a specific desired outcome.

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_2.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_2.png?raw=true" /></a></p>
<p align="center">Image from [Webopedia](https://www.webopedia.com/TERM/A/algorithm.html)</p>

We can think of a flowchart as a visual representation of the steps or procedures of an algorithm. 

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_3.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_3.png?raw=true" /></a></p>
<p align="center">Image from [C-Programming](https://www.c-programming-simple-steps.com/algorithm-definition.html)</p>

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_4.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_4.png?raw=true" /></a></p>
<p align="center">TED-Ed, "[What's an algorithm?](https://youtu.be/6hfOvs8pY1k)" *YouTube Video* (20 May 2013).</p>

We can think of the information contained in an algorithm as a type of pseudo-code that provides a set of instructions to the underlying machine. The compiler and assembler functions for the programming language we are using will “translate” the more human-readable algorithm into a discrete set of instructions for the machine.

# Artificial Intelligence

“In computer science, artificial intelligence (AI), sometimes called machine intelligence, is intelligence demonstrated by machines, in contrast to the natural intelligence displayed by humans and animals. Leading AI textbooks define the field as the study of ‘intelligent agents’: any device that perceives its environment and takes actions that maximize its chance of successfully achieving its goals. Colloquially, the term ‘artificial intelligence" is often used to describe machines (or computers) that mimic ‘cognitive’ functions that humans associate with the human mind, such as ‘learning’ and ‘problem solving.’” ([Wikipedia](https://en.wikipedia.org/wiki/Artificial_intelligence))

# Machine Learning

“Machine learning (ML) is the scientific study of algorithms and statistical models that computer systems use to perform a specific task without using explicit instructions, relying on patterns and inference instead. It is seen as a subset of artificial intelligence. Machine learning algorithms build a mathematical model based on sample data, known as ‘training data,’ in order to make predictions or decisions without being explicitly programmed to perform the task. Machine learning algorithms are used in a wide variety of applications, such as email filtering and computer vision, where it is difficult or infeasible to develop a conventional algorithm for effectively performing the task.” ([Wikipedia](https://en.wikipedia.org/wiki/Machine_learning))



## Predictive Modelling

### Predictive Analytics

“Predictive analytics encompasses a variety of statistical techniques from data mining, predictive modelling, and machine learning, that analyze current and historical facts to make predictions about future or otherwise unknown events. In business, predictive models exploit patterns found in historical and transactional data to identify risks and opportunities. Models capture relationships among many factors to allow assessment of risk or potential associated with a particular set of conditions, guiding decision-making for candidate transactions.” ([Wikipedia](https://en.wikipedia.org/wiki/Predictive_analytics))

## Machine Learning: Putting It All Together

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_5.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_5.png?raw=true" /></a></p>
<p align="center">Image from “[Artificial Intelligence: Definition Types, Examples, Technologies](https://medium.com/@chethankumargn/artificial-intelligence-definition-types-examples-technologies-962ea75c7b9b)” Medium blog post</p>

Let’s look at how these different concepts and functions work together.

Machine learning uses predictive modeling to classify or categorize an unmarked dataset. 

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_6.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_6.png?raw=true" /></a></p>
<p align="center">Image from “[Exploring Machine Learning](https://medium.com/datadriveninvestor/exploring-machine-learning-f1dc6f3ec902)” Medium blog post</p>

In this example, the raw input data includes three different types of fruit. The machine learning model interprets, processes, and classifies (or categorizes) the data to create the trained model in the algorithm’s output.

Other types of machine learning algorithms take a set of training data and use predictive modeling to classify or categorize the data.

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_7.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_7.png?raw=true" /></a></p>
<p align="center">Image from “[Machine Learning Basics](https://medium.com/@canburaktumer/machine-learning-basics-with-examples-part-2-supervised-learning-e2b740ff014c)” Medium blog post</p>

In this example, a set of already classified training data is given to the machine learning algorithm. The accuracy of the algorithm is tested by giving new raw or unlabeled data to the algorithm to see if it can classify it correctly based on the training data.

# Deep Learning

In recent years, deep learning has emerged as an advanced application of machine learning in artificial intelligence.

“Deep learning (also known as deep structured learning or differential programming) is part of a broader family of machine learning methods based on artificial neural networks with representation learning. Deep learning is a class of machine learning algorithms that uses multiple layers to progressively extract higher level features from the raw input. For example, in image processing, lower layers may identify edges, while higher layers may identify the concepts relevant to a human such as digits or letters or faces.” ([Wikipedia](https://en.wikipedia.org/wiki/Deep_learning))

## Neural Network

## Deep Learning: Putting It All Together

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_8.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_8.png?raw=true" /></a></p>
<p align="center">Model of the type of neural network used in deep learning. [Image from Wikimedia Commons](https://en.wikipedia.org/wiki/Neural_network#/media/File:Neural_network_example.svg)</p>

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_9.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_9.png?raw=true" /></a></p>
<p align="center">Another model that illustrates a basic neural network and the type of neural network used in deep learning. Image from Xing, Wanli & Du, Dongping. (2018). Dropout Prediction in MOOCs: Using Deep Learning for Personalized Intervention. Journal of Educational Computing Research. DOI: [10.1177/0735633118757015](https://www.researchgate.net/publication/323784695_Dropout_Prediction_in_MOOCs_Using_Deep_Learning_for_Personalized_Intervention).</p>

# Machine Learning Versus Deep Learning

<p align="center"><a href="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_10.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/artificial-intelligence-overview/blob/main/figures/Figure_10.png?raw=true" /></a></p>
<p align="center">Figure that illustrates the difference between machine learning and deep learning. [Image from Quora.com.](https://www.quora.com/What-is-the-difference-between-deep-learning-and-usual-machine-learning)</p>
