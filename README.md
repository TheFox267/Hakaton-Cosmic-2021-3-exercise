![Watchers][watchers-badge]
![Watchers][code-size-badge]
[![License][license-badge]][license-url]
[![Issues][issues-badge]][issues-url]
[![Issues][forks-badge]][forks-url]




<!-- PROJECT LOGO -->
  <h3 align="center">Хакатон CosmicHack - Приложение «Ракеты от SpaceX»</h3>
  <p align="center">
    <a href="https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/issues">Сообщить об ошибке</a>
    ·
    <a href="https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/issues">Запросить функцию</a>
  </p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Содержание:</summary>
  <ol>
    <li>
      <a href="#О-проекте">О проекте</a>
    </li>
    <li>
      <a href="#Что-нужно-для-запуска">Что нужно для запуска</a>
    </li>
    <li><a href="#Запуск">Запуск</a></li>
    <li><a href="#Дорожная-карта">Дорожная карта</a></li>
    <li><a href="#Лицензия">Лицензия</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## О проекте
![Product Name Screen Shot][product-screenshot]

Какие цели я себе ставил, чтобы сделать данное <a href="#Задание">задание</a>:
* Подготовить макет в приложении QtDesigner
* Получить данные с [сайта][spacex-url], о ракетах SpaceX
* Перевести нужные данные на русский язык
* Подготовить данные для добавлению их в таблицу
* Добавить данные в таблицу(QTableWidget)
* Записать данные в базу данных
* Сделать проверку наличия данных о ракетах в базе данных




### Что нужно для запуска

Установить сразу все нужные пакеты:
  ```sh
  pip install -r requirements.txt
  ```

Версия python:
* [Python~=3.8](https://www.python.org/)

Библиотеки и команда для их установки:
* requests~=2.25.1
  ```sh
  pip install requests==2.25.1
  ```
* translators~=4.7.16
  ```sh
  pip install translators==4.7.16
  ```
* loguru~=0.5.3
  ```sh
  pip install loguru==0.5.3
  ```
* PyQt5~=5.15.4
  ```sh
  pip install PyQt5==5.15.4
  ```
* SQLAlchemy~=1.4.6
  ```sh
  pip install SQLAlchemy==1.4.6
  ```




## Запуск

Нужно запустить файл **template.py**, заранее установив все библиотеки. При первом запуске нужно иметь подключение к интернету.



<!-- ROADMAP -->
## Дорожная карта

Смотреть [открытые вопросы](https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/issues) - список предложенных функций (и известных проблем).


<!-- LICENSE -->
## Лицензия

Распространяется по лицензии MIT. См. `LICENSE` для получения дополнительной информации.



<!-- Задание -->
## Задание
Американская компания по производству космической техники SpaceX имеет свой публичный API-интерфейс (см. [github](https://github.com/r-spacex/SpaceX-API)) который, в том числе, позволяет получать данные о космических ракетах компании.
Напишите программу, при помощи которой можно будет получить данные о космических ракетах компании SpaceX, выделить среди них необходимые поля: название ракет, их высоту, диаметр, массу, тип топлива, текст с описанием, ссылку на сайт Wikipedia. Полученные данные необходимо представить в таком формате, чтобы ракеты можно было отсортировать по любому из представленных полей.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-url]: https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/network/members
[issues-url]: https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/issues
[license-url]: https://github.com/TheFox267/Hakaton-Cosmic-2021-3-exercise/blob/master/LICENSE
[product-screenshot]: images/screen.png
[spacex-url]: https://api.spacexdata.com/v4/rockets/
[license-badge]: https://img.shields.io/github/license/TheFox267/Hakaton-Cosmic-2021-3-exercise
[issues-badge]: https://img.shields.io/bitbucket/issues/TheFox267/Hakaton-Cosmic-2021-3-exercise
[watchers-badge]: https://img.shields.io/github/watchers/TheFox267/Hakaton-Cosmic-2021-3-exercise
[forks-badge]: https://img.shields.io/github/forks/TheFox267/Hakaton-Cosmic-2021-3-exercise
[code-size-badge]: https://img.shields.io/github/languages/code-size/TheFox267/Hakaton-Cosmic-2021-3-exercise
