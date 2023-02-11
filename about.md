---
layout: page
title: Про курс
description: Загальна інформація.
nav_order: 1
---

# Про курс
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Базовi знання C/C++ та Python: типи даних, цикли, умови, функцiї та манiпуляцiї з масивом.
- Обiзнанiсть з NumPy, включаючи використання ndarrays та ufuncs.
- Знання англiйської: можливiсть зрозумiти основний змiст поставленого завдання.

Підручники
: 1. David Kirk and Wen-mei W. Hwu (2017). [*Programming massively parallel processors: a hands-on approach*, 3rd Edition](https://www.amazon.com/Programming-Massively-Parallel-Processors-Hands/dp/0128119861/ref=sr_1_fkmr0_2?crid=2YR2Y8FMYMZRB&keywords=Programming+Massively+Parallel+Processors%3A+A+Hands-on+Approach+3rd+Edition&qid=1643962972&s=books&sprefix=programming+massively+parallel+processors+a+hands-on+approach+3rd+edition+%2Cstripbooks-intl-ship%2C171&sr=1-2-fkmr0).

: 2. Robert (Bob) Robey and  Yuliana (Yulie) Zamora (2021). [*Parallel and High Performance Computing*](https://livebook.manning.com/book/parallel-and-high-performance-computing/chapter-1/69).


## На випадок повітряної тривоги
{% assign siren = site.slides | where: "title", "Повітряна тривога" | first %}
{{ siren.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}