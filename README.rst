|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Метод мультистилевого рендеринга изображений
    :Тип научной работы: M1P/НИР/CoIS
    :Автор: Даниил Ильич Загатин
    :Научный руководитель: кандидат физико-математических наук, Китов Виктор Владимирович

Abstract
========

This work addresses the problem of arbitrary image style transfer using convolutional neural networks. Building on the methods of Gatys, Johnson, and Ghiasi, we develop and test generator modifications with a style encoder and various integration strategies for style embeddings: concatenation, 1×1 convolutional injection, FiLM blocks, and patch-based transfer. The encoder, based on Inception-v3 and trained on WikiArt, was combined with content images from MS COCO. Experiments show that models reproduce color palettes and basic textures but fail to capture distinctive stylistic features, often converging to averaged strokes and tones. The main limitation is the weak training dynamics of the style encoder, leading to uninformative embeddings. The study identifies architectural bottlenecks and suggests improvements, including stronger encoder training, decomposition of style components, and alternative loss formulations.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
