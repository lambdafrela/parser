# My Little Parser

Этот репозиторий содержит готовый код парсера, который мы разбираем в лекциях.

## Структура
Репозиторий состоит из трех веток:

1. `main` - тут лежит оригинальная версия парсера, написанная @Euphe
2. `functional` - версия парсера, написанная в [функциональном](https://ru.wikipedia.org/wiki/%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5) стиле
3. `object_oriented` - версия парсера, написанная в стиле ООП

## Возможности

- [X] Получение списка топ-100 книг и авторов с сайтов:
  - [X] [LiveLib](http://www.livelib.ru/books/top)
  - [X] [ReadRate](http://readrate.com/rus/ratings/top100)
  - [X] [Readly](http://readly.ru/books/top)
- [X] Сохранение результатов в файл `txt`
- [ ] Веб-интерфейс
- [ ] Обработка динамических страниц

## Совершенствуем парсер!

Объединившись вместе, мы можем написать крутой и красивый парсер, а также сделать его более универсальным.  
#### **Инструкция по принятию участия в проекте [ТУТ](.github/CONTRIBUTING.md)** :godmode:.

## Создаем virtualenv

Описываю для win, но особой разницы нет, да и уповаю на сообразительность линуксоидов =)
Создадим окружение внутри проекта:

`> cd %путь до папки с проектом%`
`> virtualenv env`

env - название папки с виртуальным окружением, можете выбрать любое.
Теперь в папке с нашим проектом запустим

`> ../env/Scripts/activate`
Эта строка на время даст возможность запускать pip или python из venv одноименными командами без указания абсолютного пути.

Далее установим requirements, если мы не в папке с `requirements.txt`, то используем абсолютный путь до него:

`> pip install -r requirements.txt #использован относительный путь` 

Теперь программу можно запустить с помощью `> python %путь до программы%`



