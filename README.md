HarrixOptimizationAlgorithms
============================

Версия 1.5

Сборник описаний алгоритмов оптимизации нулевого порядка. Это своеобразная "свалка" алгоритмов, которые используются автором. На данный документ можно ссылаться в своих работах, чтобы указать, что тот или иной алгоритм оптимизации подробно описан в этом документе. Тут нет исследований эффективности алгоритмов с данными операторами - это задача иных проектов. Здесь представлено только описание алгоритмов.

https://github.com/Harrix/HarrixOptimizationAlgorithms

Данные распространяются по лицензии [Apache License, Version 2.0](../master/LICENSE.txt).

Непосредственно главный файл: [**_HarrixOptimizationAlgorithms.pdf**](../master/_HarrixOptimizationAlgorithms.pdf).

Прямая ссылка на скачивание: [**_HarrixOptimizationAlgorithms.pdf**](https://raw.github.com/Harrix/HarrixOptimizationAlgorithms/master/_HarrixOptimizationAlgorithms.pdf).

Тестирование алгоритмов представлено тут:

https://github.com/Harrix/HarrixDataOfOptimizationTesting

Установка
---------

Прочитать подробно об установке можно тут http://blog.harrix.org/?p=1229.

Список алгоритмов
-----------------

 * **MHL_StandartBinaryGeneticAlgorithm** - стандартный генетический алгоритм для решения задач на бинарных строках;
 * **MHL_StandartRealGeneticAlgorithm** - стандартный генетический алгоритм для решения задач на вещественных строках;
 * **MHL_BinaryGeneticAlgorithmWDPOfNOfGPS** - генетический алгоритм для решения задач на бинарных строках с изменяющимся соотношением числа поколений и размера популяции;
 * **MHL_RealGeneticAlgorithmWDPOfNOfGPS** - генетический алгоритм для решения задач на вещественных строках с изменяющимся соотношением числа поколений и размера популяции;
 * **MHL_BinaryGeneticAlgorithmWDTS** - генетический алгоритм для решения задач на бинарных строках с турнирной селекцией, где размер турнира изменяется от 2 до размера популяции;
 * **MHL_RealGeneticAlgorithmWDTS** - генетический алгоритм для решения задач на вещественных строках с турнирной селекцией, где размер турнира изменяется от 2 до размера популяции;
 * **MHL_BinaryGeneticAlgorithmWCC** - генетический алгоритм для решения задач на бинарных строках, в котором есть только два вида скрещивания: одноточечное и двухточечное скрещивание с возможностью полного копирования одного из родителей;
 * **MHL_RealGeneticAlgorithmWCC** - генетический алгоритм для решения задач на вещественных строках, в котором есть только два вида скрещивания: одноточечное и двухточечное скрещивание с возможностью полного копирования одного из родителей;
 * **MHL_BinaryGeneticAlgorithmTournamentSelectionWithReturn** - генетический алгоритм для решения задач на бинарных строках с турнирной селекцией с возвращением, где размер турнира изменяется от 2 до размера популяции;
 * **MHL_RealGeneticAlgorithmTournamentSelectionWithReturn** - генетический алгоритм для решения задач на вещественных строках  с турнирной селекцией с возвращением, где размер турнира изменяется от 2 до размера популяции.
 
Скриншоты
-------------------

![alt text](../master/images/scheme.png "Пример схемы алгоритма")

Про структуру проекта
---------------------

Файл [**_HarrixOptimizationAlgorithms.pdf**](../master/_HarrixOptimizationAlgorithms.pdf) - это непосредственно сам документ "_HarrixOptimizationAlgorithms. Сборник описаний алгоритмов оптимизации". В нем располагаются описания алгоритмов.

В корневой папке находятся две папки. 

В папке [**Source**](../master/Source) располагаются файлы непосредственно документа, где находится файл [**_HarrixOptimizationAlgorithms.tex**](../master/Source/_HarrixOptimizationAlgorithms.tex) (это исходник pdf документа) и файлы, которые являются вспомогательными для [**_HarrixOptimizationAlgorithms.tex**](../master/Source/_HarrixOptimizationAlgorithms.tex).

В папке [**images**](../master/images) находятся служебные рисунки для отображения в этом файле.

Сведения для редактирования файлов
----------------------------------

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции \*.tex документов в \*.pdf. Автор использует для этого связку [MiKTex](http://www.miktex.org/) и [TeXstudio](http://texstudio.sourceforge.net/). 

В варианте, который использует автор, в \*.tex файлах справок для отображения русских букв используется модуль pscyr. Об его установке можно прочитать (и скачать) в статье http://blog.harrix.org/?p=444.

Подробное описание установки и настройки связки MiKTeX + TeXstudio + pscyr можно прочитать в статье http://blog.harrix.org/?p=849.

Использованные технологии
-------------------------

- [LaTeX](http://ru.wikipedia.org/wiki/LaTeX), [MiKTeX](http://miktex.org/), [BiBTex](http://ru.wikipedia.org/wiki/BibTeX), [TeXstudio](http://texstudio.sourceforge.net/), [PSCyr](http://blog.harrix.org/?p=444).
- [HarrixLaTeXDocumentTemplate](https://github.com/Harrix/HarrixLaTeXDocumentTemplate).
 
История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу [sergienkoanton@mail.ru](mailto:sergienkoanton@mail.ru) или  [http://vk.com/harrix](http://vk.com/harrix).

Сайт автора, где публикуются последние новости: [http://blog.harrix.org](http://blog.harrix.org), а проекты располагаются по адресу: [http://harrix.org](http://harrix.org).