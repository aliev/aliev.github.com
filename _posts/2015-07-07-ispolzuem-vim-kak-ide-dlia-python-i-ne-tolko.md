---
layout: post
title: Используем Vim как IDE для Python и не только
tags: "python, vim"
category: ru
published: false
---

Чтобы там не говорили любители IDE, Vim лучший из лучших. И как редактор и как IDE. Я говорю это с уверенностью как чловек, активно использующий данный редактор уже многие годы. Результат моего труда [можно посмотреть в моем репозитории](https://github.com/aliev/vim).

На самом деле я сам многие годы метался между Vim и другими текстовыми редакторами, но всегда возвращался обратно. Что тут поделать, соблазн есть соблазн. Из того, чем я успел воспользоваться: Emacs, Sublime, PyCharm, PyDev, Vico, TextMate и даже дибильный Atom.io. Ни один из этих редакторов не удовлетворял моих потребностей.

Данную статью я разделю на несколько заголовков. Я расскажу какие средства и приложения я использую в процессе разработки, и что из этого у меня получилось интегрировать в мой любимый редактор.

Так как я разработчик на Python, пожалуй начну с него.


## Python и jedi-vim

Это один из самых быстрых и универсальных плагинов, который не является комбайном и включает умный автокомплит питона в редактор. Расширение очень активно развивается, и я вижу новые коммиты почти каждый день. Кроме автокомплита он поддерживает функцию рефакторинга (правда работает эта функция пока что не очень стабильно), go to definition и go to declaration. Так же он имеет замечательную команду Pyimport, которой можно быстро открыть питоновский пакет по его названию.