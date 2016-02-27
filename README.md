# Assignment 1
Изучаем Git.
Git это популярная распределенная система контроля версий.
Она позволяет людям эффективно работать над програмными продуктами вместе.
Даже если вы работаете один, контроль версий поможет вам лучше понимать свой код и даст возможность экперементировать, 
не боясь потерять код.

Вы можете легко выложить git проект на бесплатный git хостинг.
GitHub хорошо подходит для открытых проектом.
Для закрытых проектов можно использовать https://bitbucket.org/ 

## Установка git

1. Скачайте и установите git c [официального сайта](https://git-scm.com/download/win).
1. При установке рекомендованная конфигурацию:
  * Use git and optional unix tools from windows prompt (последняя опция, содержащая красный warning)
  * Checkout windows style, checking unix style (первая опция, дефолт)
  * Use windows default console windows (вторая опция)

Чтобы проверить что все установилось нормально откройте `cmd` или `powershell`

```
> git
```

вы должны увидеть git help

## Настройка

Там же укажите следующее, заменив "John Doe" и johndoe@example.com

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

**NB**: эта информация будет записываться в каждый коммит.
Когда вы выкладываете код в публичное пространство, эта информация становится легко доступной.
Некоторые люди предпочитают скрывать свой настоящий email и использовать [фиктивный](https://help.github.com/articles/keeping-your-email-address-private/).
Лично я никогда это не использовал и не имел никаких проблем со спамом.

## Установка githug

Мы будем использовать https://github.com/Gazler/githug для обучения.
**Githug** позволяет стать мастером git за пару часов.

1. Утсановите [ruby 2.2.4](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.4-x64.exe)
  * При установке отметьте checkbox "Add Ruby to PATH"
1. Запустите новое окно `cmd` или `powershell`
1. `gem install githug`

У вас должна появится новая команда `githug`

## Задание

Мы начнем решать уровни githug вместе, завершить их и есть 1ое задание.
