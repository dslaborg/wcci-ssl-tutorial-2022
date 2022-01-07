---
layout: default
---

test

# Table of Contents
1. [Tutorial abstract](#tutorial_abstract)
2. [Topic overview](#topic_overview)
3. [Outline of tutorial structure](#outline_of_tutorial_structure)
    1. [Part 1. Introduction to self-supervised learning and its applications (1 hour)](#introduction_to_ssl)
    2. [Part 2. Hands-on experience with self-supervised learning (30 minutes)](#hands-on_experience)

* * *


<a id='tutorial_abstract'></a>
# Tutorial abstract
Supervised deep learning has seen tremendous success, but relies on large amounts of carefully labeled data that are not readily available in many application domains. This inspired the development of alternative approaches, among which self-supervised learning has seen rapid progress and quick adoption in various fields, ranging from natural language processing to image and speech recognition. In self-supervised learning, neural networks are trained on large, unlabeled datasets using pretext tasks (pretraining) before being trained on a downstream task in a supervised manner on (usually much) smaller, labeled datasets (fine-tuning). Self-supervised learning approaches promise to produce robust models that can be adapted to different tasks in a data-efficient way and even begin to outperform supervised approaches.

This tutorial provides an overview and introduction to self-supervised learning for a broad audience, ranging from practitioners to researchers and engineers, who want to become familiar with this exciting and emerging area of deep learning. We will focus on key concepts and ideas, including contrastive and non-contrastive approaches and their applications in various domains. The tutorial will also provide a hands-on experience where participants can try out self-supervised learning using Python and Jupyter Notebooks.

* * *


<a id='topic_overview'></a>
# Topic overview
Within the last three years, self-supervised learning (SSL) has emerged as an important approach for training large neural networks in various domains. For example, impressive advances in natural language processing were made possible by SSL trained language models (such as BERT). These successes inspired research of SSL methods in other communities working with data of different topologies (e.g., computer vision (SimCLR), speech recognition (wave2vec), or graphs). Recent months have seen progress being made with contrastive self-supervised learning methods. Building upon the ideas of contrastive learning, non-contrastive methods are another focus of the field and aim to address shortcomings of contrastive approaches (such as large minibatch sizes and false negatives). Thus, non-contrastive methods are expected to become particularly relevant for practitioners in the future.

At IJCNN, there has been no tutorial on self-supervised learning in recent years. Given the rapid developments in this field and its increasing importance for research and practical applications, we would like to provide a didactic introduction to self-supervised learning that is aimed at a broad audience and novices in this field. The tutorial will focus on key concepts and architectures that will provide participants with the foundation for understanding advanced concepts they are likely to encounter at the conference.

* * *


<a id='outline_of_tutorial_structure'></a>
# Outline of tutorial structure
<a id='introduction_to_ssl'></a>
## Part 1. Introduction to self-supervised learning and its applications (1 hour)

We introduce key concepts and ideas of self-supervised learning, focusing on fundamental aspects and challenges in this rapidly emerging field. We cover different approaches, including contrastive methods (such as SimCLR and MoCo) and recent non-contrastive methods (e.g., SwAV, BYOL, SimSiam, VICReg). We highlight selected applications that profited from self-supervised training.

<a id='hands-on_experience'></a>
## Part 2. Hands-on experience with self-supervised learning (30 minutes)

We will guide participants through an applied project on self-supervised learning. We will provide code, data, and instructions (using Python and Jupyter notebooks) so that participants can have hands-on experience with self-supervised learning and deepen their understanding gained in the first part of the tutorial. Participants do not have to actively participate in this exercise, but we would like to give them the opportunity to experience SSL firsthand.
