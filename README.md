# [vectree](http://vectree.ru/)

[![license][license-badge]][LICENSE] [![Codacy Badge](https://api.codacy.com/project/badge/Grade/96071bdddd4548eba86b955593671ec4)](https://www.codacy.com/app/vectree/resources?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=vectree/resources&amp;utm_campaign=Badge_Grade)
[![Join the chat at https://gitter.im/vectree-chat/Lobby](https://badges.gitter.im/vectree-chat/Lobby.svg)](https://gitter.im/vectree-chat/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![alt text](https://sun9-7.userapi.com/c841624/v841624284/28b96/aJT1-hf8yts.jpg)

В данном репозитории представлены дорожные карты (roadmap), тесты, задания на различные темы из мира программирования. Кроме репозитория был создан сайт Vectree, на котором выставлены все материалы в более удобном виде.

Vectree — платформа для начинающих разработчиков, помогающая приобрести ключевые навыки для трудоустройства в IT.

Наша задача:
- предоставление образовательных материалов,
- проверка знаний, 
- менторская поддержка,
- консультация в карьерных вопросах,
- формирование команд для работы над реальными задачами,
- трудоустройство.

## Разделы
* [Задания](https://github.com/vectree/resources#Задания)
* [Тесты](https://github.com/vectree/resources#Тесты)
* [Карты](https://github.com/vectree/resources#Карты)

## Задания
#### Структура заданий
Каждое задание содержит *README.md* файл с введением и общим описанием. В папке *issues* могут содержаться последовательные шаги по решению задания. 
```
|-- 1 # Номер задания
    |-- README.md # Введение
    |-- issues
        |-- 00 Подготовка.md # Шаг 1
        |-- 01 Граббер.md # Шаг 2
        |-- 02 Цикл.md # Шаг 3
```

#### Список доступных заданий
- Java:
  * [Conway's Game of Life](https://vectree.ru/task/0/0)
  * [Арбитражный бот](https://vectree.ru/task/0/5)
- JUnit:
  * [Тестирование алгоритмов сортировки](https://vectree.ru/task/0/6)
  * [Тестируем терминал продуктового магазина](https://vectree.ru/task/0/7)
- Maven:
  * [Youtube Trends](https://vectree.ru/task/0/8)
- Spring:
  * [Курс валют](https://vectree.ru/task/0/9)
  * [Pomodoro](https://vectree.ru/task/0/10)
- Go:
  * [Go Grabber](https://vectree.ru/task/0/1)
  * [Go Web App](https://vectree.ru/task/0/2)
  * [Go Skimmer](https://vectree.ru/task/0/3)
- Docker:
  * [Кластер на AWS](https://vectree.ru/task/0/4)
- STM:
  * [Знакомство](https://vectree.ru/task/0/11)
  * [Работа с портами ввода / вывода](https://vectree.ru/task/0/12)
  * [Прерывания](https://vectree.ru/task/0/13)
  * [Таймеры](https://vectree.ru/task/0/14)
  * [FreeRTOS на STM32](https://vectree.ru/task/0/15)
- SSE:
  * [Векторные операции с SSE](https://vectree.ru/task/0/16)
- CUDA:
  * [Разработка на CUDA](https://vectree.ru/task/0/17)
  * [Преобразование Фурье](https://vectree.ru/task/0/18)
- HTML / CSS / Bootstrap:
  * [Резюме](https://vectree.ru/task/0/19)
- JavaScript:
  * [Создаем несколько игр и не только!](https://vectree.ru/task/0/19)
  * [Пинг-понг](https://vectree.ru/task/0/20)
    
#### Список доступных командных заданий
- Java:
  * [Биллинговая система](https://vectree.ru/task/0/22)
- Go:
  * [Интерфейс управления Docker-контейнерами](https://vectree.ru/task/0/23)

## Тесты
#### Оформление Quiz
- Одна тема (topic) - одна квиза
- Каждое направления связанно с одной или несколькими квизами
 
Шаблон файла c квизой

- **quizId** - id теста. Нумерация по порядку от 0 и совпадет с названием файла, в котором лежит квиза
- **minPercent** - процент правильных ответов, для прохождения теста. (значения от 0 до 100)
- **topicName** - тема, к которой относится тест
- **limit** - количесто вопросов, которое будет показано при прохождении теста
- **questions** - массив объектов, каждый из которых содержит вопрос, варианты ответов и номер правильных ответов

#### Список доступных тестов
- [Java](https://vectree.ru/quiz/0/1)
- [JUnit](https://vectree.ru/quiz/0/5)
- [Maven](https://vectree.ru/quiz/0/3)
- [Spring](https://vectree.ru/quiz/0/6)
- [J2EE](https://vectree.ru/quiz/0/7)
- [Go](https://vectree.ru/quiz/0/8)
- [Docker](https://vectree.ru/quiz/0/9)
- [PostgreSQL](https://vectree.ru/quiz/0/2)
- [STM](https://vectree.ru/quiz/0/11)
- [Git](https://vectree.ru/quiz/0/4)
- [FreeRTOS](https://vectree.ru/quiz/0/12)
- [CUDA](https://vectree.ru/quiz/0/14)
- [SSE](https://vectree.ru/quiz/0/13)
- [HTML / CSS / Bootstrap](https://vectree.ru/quiz/0/15)
- [JavaScript](https://vectree.ru/quiz/0/16)
- [MongoDB](https://vectree.ru/quiz/0/17)

## Карты

#### Оформление Digest
- Блоки выравнивать
- В title пишем темы, которые рассматриваются на карте
- В одном блоке стараемся хранить от 2-5 ссылок
- Формат creator для статей: 
  * С большой буквы
  * Не сайт, а название сайта (Например Stepik, а не stepic.com)
  * Статьи на хабру без автора (Habrahabr)
- В темах стараемся обобщать. Используем их в title
- Сокращаем текст => блоки компактнее + стараемся не делать широкие строки в creator
- Основные типы блоков: Видео, Онлайн-курсы, Интерактивные сервисы, Статьи, Задачники, Полезные ссылки, Книги. (Если нужны новые обсуждаем)
- В секциях пишем уроки, лекции, главы в которых встречается материал
- Если все темы присутствуют в материале, пишем: "Все необходимые темы"
- Орфография!!! 
- Сравнивайте свою картру с другими картами

#### Список отдельных дайджестов
- [Java Code Style](https://vectree.ru/digest/0/18)
- [Инструменты анализа кода Java](https://vectree.ru/digest/0/22)
- [Инструменты анализа кода Go](https://vectree.ru/digest/22/1/0)
- [Bash-терминал](https://vectree.ru/digest/22/1/0)
- [Travis CI](https://vectree.ru/digest/0/21)
- [Циклы разработки](https://vectree.ru/digest/0/23)
- [Gorilla Web Toolkit](https://vectree.ru/digest/0/29)
- [Rabbit MQ](https://vectree.ru/digest/0/34)
- [Микросервисы](https://vectree.ru/digest/0/35)
- [Английский](https://vectree.ru/digest/0/41)
- [Введение в программирование](https://vectree.ru/digest/0/41)

[LICENSE]: ./LICENSE.md
[license-badge]: https://img.shields.io/badge/license-MIT-blue.svg


