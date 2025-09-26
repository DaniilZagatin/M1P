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
    :Тип научной работы: M1P
    :Автор: Загатин Даниил Ильич
    :Научный руководитель: кандидат физико-математических наук, доцент Китов Виктор Владимирович

Abstract
========

В работе рассматривается задача произвольной стилизации изображений с использованием сверточных нейронных сетей. На основе методов Гатиса, Джонсона и Гиаси исследованы модификации генератора с кодировщиком стиля и различными способами внедрения эмбеддингов: конкатенация, 1×1-инъекция, FiLM-блоки и патчевый метод. В качестве кодировщика применены слои Inception-v3, дообученные на WikiArt, а в качестве контента использовались изображения MS COCO. Эксперименты показали, что модели успешно передают палитру и текстурные элементы, однако не воспроизводят уникальные стилистические особенности, склоняясь к усреднённым мазкам и цветам. Главной проблемой стала низкая информативность стилевых эмбеддингов и слабое обучение кодировщика. Работа выявляет архитектурные ограничения и предлагает направления улучшений: усиление тренировки кодировщика, раздельное внедрение компонентов стиля и использование альтернативных функций потерь.

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
