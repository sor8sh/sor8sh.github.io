---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<ul>
    {% for post in site.projects %}
        {% include archive-single-cv.html %}
    {% endfor %}
</ul>

* B.Sc. Final Project (Spring 2019)
    * Advisor: Dr. Sauleh Etemadi
    * [Image Captioning using Attention Mechanism trained on MSCOCO dataset.](https://sor8sh.github.io/files/BSc-Final-Project.md) (TensorFlow)
* Foundation of Computer Vision (Fall 2018)
    * Course final project: Room Segmentation (OpenCV)
    * Noise Reduction, Line Detection, Morphology, Image Classification, Template Matching Face Detection with Kalman Filter, Corner Detection, CamScanner (OpenCV)
* Machine Learning Lab (Summer 2018)
    * Using transfer learning in Deep Reinforcement Learning to speed up the training phase of an agent learning how to play ATARI 2600 games.
* Computational Intelligence (Spring 2018)
    * Image classification with an MLP Neural Network using MNIST dataset (Keras)
    * Function approximation with an RBF Neural Network (Python)
    * Designing a Fuzzy controller for Inverted Pendulum problem (FCL)
    * Solving 8-Queen problem using Genetic Algorithm (Python)
* Natural Language Processing (Spring 2018)
    * Anagram: Finding all Anagrams for a Persian word (Python)
    * Machine Translation: Translating from Persian to Quran-style Arabic (OpenNMT)
    * Sentiment Analysis for a Twitter accounts tweets with unsupervised learning (Python)
    * WordCloud: Classifying textual data using Naive Bayes (Vopal Wabbit, Mallet)
* Artificial Intelligence (Fall 2017)
    * Sentiment Analysis for IMDB reviews using Naive Bayes & Decision Tree classifiers (NLTK)
* Computer Architecture (Spring 2017)
    * Designing a CPU that could find a specific number in an array of numbers (Xilinx ISE)
* Advanced Computer Programming (Spring 2016)
    * Web Scrapper, Social Network, Search Engine, File Manager (Python)