---
## Front matter
lang: ru-RU
title: "Лабораторная работа № 6"
subtitle: "Мандатное разграничение прав в Linux"
author: "Абакумов Егор Александрович"

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux. Проверить работу SELinx на практике совместно с веб-сервером Apache.

# Ход работы

## Проверка состояния SELinux

![](image/pres/1.png){ #fig:001 width=72% }

## Проверка состояния демона httpd

![](image/pres/2.png){ #fig:002 width=72% }

## Статистика через seinfo

![](image/pres/3.png){ #fig:003 width=72% }

## Проверка доступа к файлу через браузер

![](image/pres/4.png){ #fig:004 width=72% }

## Изменение контекста безопасности файла

![](image/pres/5.png){ #fig:005 width=72% }

## Повторная проверка доступа к файлу через браузер

![](image/pres/6.png){ #fig:006 width=72% }

## Список доступных httpd портов

![](image/pres/7.png){ #fig:007 width=72% }

## Повторная проверка доступа к файлу браузером через 81-ый порт

![](image/pres/8.png){ #fig:008 width=72% }

## Вывод

В ходе работы мы успешно развили навыки администрирования ОС Linux, получили первое практическое знакомство с технологией SELinux и проверили работу SELinx на практике совместно с веб-сервером Apache.