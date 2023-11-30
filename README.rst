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

    :Название исследуемой задачи: Нейросетевой подход к обучению векторных представлений мультимодальных данных с использованием угловых аддитивных функций потерь
    :Тип научной работы: НИР
    :Автор: Черникова Полина Георгиевна
    :Научный руководитель: д.ф.-м.н, Воронцов Константин Вячеславович
    :Научный консультант(при наличии): -

Abstract
========

В данной работе рассматривается задача обучения метрического представления мультимодальных данных. Для ее решения предлагается новый подход обучения с учителем на основе сферического классификатора и аддитивных угловых функций потерь.  
Предлагаемый подход состоит из двух основных компонентов: 1) двухуровневой архитектуры на базе трансформеров; 2) аддитивной угловой функции потерь, напрямую оптимизирующей сферическое расстояние между объектами.
Эксперименты показали, что данный подход позволяет ускорить обучение, получить более разделимые и геометрически интерпретируемые векторные представления по сравнению с классическими подходами.
Предложенная архитектура легковесна, эффективно скалируется при увеличении количества данных и модальностей, не требуя перебора комбинаторного числа пар, как контрастивное обучение. 

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
