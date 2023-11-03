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

    :Название исследуемой задачи: Нейросетевые методы обучения метрических векторных представлений для мультимодальных данных 
    :Тип научной работы: НИР
    :Автор: Черникова Полина Георгиевна
    :Научный руководитель: д.ф.-м.н, Воронцов Константин Вячеславович
    :Научный консультант(при наличии): -

Abstract
========

Задача обучения метрического представления мультимодальных данных, семантически информативного и одновременно устойчивого к шуму и пропущенным данным до сих пор остается актуальной проблемой, так как и для обучения глубоких сетей, и для рекомендательных систем, и для решения практических задач, таких как информационных поиск, классификация и кластеризация, используются данные разной природы.  Основным подходом обучения таких представлений является нейросетые методы на основе contrastive learning. Однако этот подход требует много данных и их тщательной подготовки, что занимает много времени и вычислительных ресурсов. В данной работе рассматривается подход к обучению метрического представления мультимодальных данных на основе класификационных сферических голов по типу ArcFace. В качестве основных модальностей используется текст, табличные данные (категориальные и числовые признаки), а также графовые представления взаимосявей и взаимодействей. Предлагаемая архитектура состоит из 2 основных компонент: 1) двухуровневая архитектура, состоящая из трансформерных моделей, специфичных для каждой модальности, и нейронной сети, проецирующей сконкатенированные представления каждой модальности в общее латентное представление; 2) additive angular margin loss, который оптимизирует напрямую сферическое расстояние между мультимодальными объектами, тем самым увеличивая межклассовое расстояние, уменьшая внутриклассовое.

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
