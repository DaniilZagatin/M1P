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

В данной работе рассматривается задача произвольной стилизации изображений с использованием сверточных нейронных сетей (CNN). Большинство существующих моделей обучаются для конкретного стиля и успешно передают цветовые палитры и текстурные элементы; однако они часто не воспроизводят уникальные стилистические особенности, склоняясь к усреднённым мазкам и цветам. Основываясь на методах Гатиса, Джонсона и Гиаси, исследуются модификации архитектуры генератора с внедрением кодировщика стиля и различными стратегиями интеграции эмбеддингов: конкатенацией, 1×1-инъекцией, FiLM-блоками и патчевыми методами. Работа выявляет архитектурные ограничения и предлагает направления улучшений, включая усиленную тренировку кодировщика стиля, раздельное внедрение компонентов стиля и использование альтернативных функций потерь. В результате разработана мультистилевая лёгкая архитектура, обеспечивающая высокое качество стилизации при сохранении гибкости применения к разнообразным стилям.

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
