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

This work explores arbitrary image style transfer with convolutional neural networks. Building on Gatys, Johnson, and Ghiasi, we test generator modifications with a style encoder and several embedding integration methods, including concatenation, 1×1 injection, FiLM blocks, and patch-based transfer. Experiments on MS COCO and WikiArt show that while models reproduce colors and textures, they fail to capture distinctive stylistic features due to weak style embeddings. The study outlines architectural limitations and suggests improvements through enhanced encoder training and alternative loss functions.

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
